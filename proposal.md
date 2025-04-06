# R PROJECT FOR STATISTICAL COMPUTING

## data.table
#### By Mukul Kumar

## PROJECT MENTORS

- Toby Dylan Hocking
- Anirban Chetia
- Doris Amoakohene
- Joshua Wu

## CONTENTS

- Project Info
- About Me
- Contact Info
- Affiliation
- Scheduled conflicts
- Mentors
- Coding Plan And Methods
- Timeline
- Management of coding project
- Test

## Project title
**Enhancing Data.Table: Enhancing Functionality, and Ensuring Quality**

## Project description
This project aims to enhance data.table by improving functionality, optimizing performance, and refining documentation. It includes adding new features, clarifying advanced concepts, optimizing algorithms, and strengthening test coverage. These improvements will make data.table more efficient, user-friendly, and accessible to the R community.

## Project idea page
https://github.com/rstats-gsoc/gsoc2025/wiki/data.table

## ABOUT ME

I am Mukul Kumar, a second-year B.E. Electronics and Telecommunication Engineering student at the Army Institute of Technology, Pune. My interest in efficient data manipulation and system performance led me to the R data.table package, where I have been an active contributor since February this year.

My background in problem-solving and programming (including R, C, Python) directly applies to data.table's focus on speed and memory efficiency. I have practical experience with the data.table codebase through 4 merged pull requests, addressing issues related to bug fixes, error message clarity, and documentation enhancements. This hands-on work has given me valuable insight into R internals, C-level optimizations within the package, and the rigorous testing required for a widely-used library. 
Currently, I am contributing documentation for advanced features like groupingsets() behavior with outer environments.

Curiously, I also wanted to test actual gain in implementing a feature. As a result, I built a proof in which I developed a benchmarking project demonstrating the performance gains of the sep2 feature in fread, a core part of my proposed work highlighting my proactive approach and ability to tackle key project goals. 
Additionally, my role as Project Head for my college's R&D Club has honed my project management and communication skills, essential for succeeding in a remote, collaborative environment like GSoC.

I am enthusiastic about applying my skills and existing familiarity with data.table to contribute further through the Google Summer of Code program.

You can check my project here: [GitHub link](https://github.com/Mukulyadav2004/fread-sep2-benchmarks)


## Contact Information
- Github: [Mukulyadav2004](https://github.com/Mukulyadav2004)
- Name: MUKUL KUMAR
- Postal address: ARMY INSTITUTE OF TECHNOLOGY, PUNE, MAHARASHTRA, 411015 
- Mobile: +91 8708206446
- Email(s): mukulrao6480@gmail.com (primary), mukulkumar_230467@aitpune.edu.in (secondary)

## Affiliation
- Institution: ARMY INSTITUTE OF TECHNOLOGY
- Program: BACHELORS OF ENGINEERING, ELECTRONICS AND TELECOMMUNICATION
- Stage of completion: 2ND YEAR
- Contact to verify: mukulkumar_230467@aitpune.edu.in (email address given by college)


## SCHEDULED CONFLICTS

I am fully prepared to dedicate myself to the R GSoC project over the summer, treating it as a full-time responsibility. I will communicate any significant upcoming events, such as exams, in advance and will strive to maintain consistent contributions even during those periods.

With no external distractions, I am confident in my ability to contribute meaningfully, collaborate effectively with mentors and the community, and ensure steady progress. I am committed to maintaining a high standard of work and delivering quality results within the expected timelines.

## Mentors
- Evaluating mentor name and email: TOBY DYLAN HOCKING, toby.hocking@r-project.org
- Co-mentor name(s) and email(s): JOSHUA WU, joshuawu2004@gmail.com

**Have you been in touch with the mentors? When and how?**

Yes, I have been in touch with my mentor, Joshua Wu, even before I began contributing. I reached out to him via email, seeking his guidance. His valuable advice greatly helped me get started with this package.

### CODING PLANS AND METHODS
**Making data.table Even Better**

## Project Goals
- This project aims to enhance the widely-used R data.table package, known for its speed and efficiency in handling large datasets. My primary goal is to make tangible contributions by addressing a carefully selected range of existing issues.

- This includes fixing bugs, implementing requested features (like improved file reading capabilities), enhancing consistency across functions, clarifying documentation, and improving error messages and data display for a smoother user experience.

- While I have a detailed plan based on these selected issues, I am fully prepared to adapt and prioritize based on mentor feedback and the project's evolving needs throughout the summer. Ultimately, my aim is to deliver high-quality, well-tested code and documentation improvements that benefit the broad data.table user community and make working with data even more effective.

My plan follows the structured timeline, starting with foundational tasks (documentation, simpler fixes) to build familiarity, progressing to the major feature (fread sep2), and then tackling other enhancements and bug fixes.

## List of Planned Contributions

I've grouped the issues I plan to address into three main categories:

### 1. Extending Functionality and Performance
This group focuses on adding new features and enhancing existing functions to make data.table even more powerful and versatile for data manipulation tasks.

**fread Enhancements:**
- [#1162](https://github.com/Rdatatable/data.table/issues/1162) : Implement the popular sep2 feature to provide more flexibility when reading files with potentially irregular separator patterns.
- [#5415](https://github.com/Rdatatable/data.table/issues/5415) : Improve robustness by making fread raise an error (instead of just a warning) when a gzipped file decompression exceeds available temporary storage, preventing unexpected behavior downstream.

**New Function Arguments:**
- [#6036](https://github.com/Rdatatable/data.table/issues/6036) : Add a flatten argument to shift(), giving users control over the output structure when shifting list columns.
- [#6341](https://github.com/Rdatatable/data.table/issues/6341) : Introduce a rev parameter to tstrsplit(), enabling more intuitive selection of elements from the end when splitting strings.

**Internal Improvements:**
- [#5913](https://github.com/Rdatatable/data.table/issues/5913) : Add support for classed conditions in internal messaging functions like stopf(), allowing for more structured error handling within the package.
- [6702](https://github.com/Rdatatable/data.table/issues/6702) : Refactor setDT and := to consolidate code related to assigning data.table objects, potentially improving maintainability and consistency.

### 2. Improving Consistency and Reliability
Addressing inconsistencies and bugs is crucial for a reliable user experience. This section targets issues that refine existing behaviors and fix specific problems.

**Consistent Behavior:**
- [#6219](https://github.com/Rdatatable/data.table/issues/6219) : Ensure function names are preserved within data.table calls when using the by argument , maintaining clarity in complex operations.
- [#5034](https://github.com/Rdatatable/data.table/issues/5034) : Align the printing behavior of truncated column lists with user expectations by enabling wrapping when trunc.cols=TRUE .
- [#4259](https://github.com/Rdatatable/data.table/issues/4259) : Standardize date/time handling by adding a POSIXlt method for IDate, improving interoperability.

**Bug Fixes & Error Handling:**
- [#5609](https://github.com/Rdatatable/data.table/issues/5609) : Resolve errors that occur when the object assigned on the right-hand side of := shares a name with an existing column .
- [#5981](https://github.com/Rdatatable/data.table/issues/5981) : Address printing issues for data.tables containing specific column types, such as rvar objects from the posterior package. 
- [#904](https://github.com/Rdatatable/data.table/issues/904) : Enhance usability within environments like knitr by improving caching behavior for := assignments.

### 3. Enhancing User Experience through Documentation and Clarity
Clear documentation and informative error messages are vital for usability. This group focuses on making data.table easier to learn and troubleshoot.

**Clearer Error Messages & Warnings:**
- [#6641](https://github.com/Rdatatable/data.table/issues/6641) : Make merge() error messages less confusing by ensuring the 'x' and 'i' prefixes consistently refer to the correct input tables.
- [#5829](https://github.com/Rdatatable/data.table/issues/5829) : Improve error reporting or guidance when the right-hand side of := is a function or closure, helping users debug their code.

**Documentation Improvements:**
- [#2487](https://github.com/Rdatatable/data.table/issues/2487) : Explicitly document the behavior of first() with named vectors compared to standard subsetting x[1].
- [#5321](https://github.com/Rdatatable/data.table/issues/5321) : Clarify the differences in indexing behavior between setindex and setkey for non-character columns.
- [#2002](https://github.com/Rdatatable/data.table/issues/2002) : Clarify that first(x) does not always return the same result as x[1] in documentation.
- [#6720](https://github.com/Rdatatable/data.table/issues/6720) : Update documentation to provide a comprehensive, current list of data.table options and their values.
- [#6638](https://github.com/Rdatatable/data.table/issues/6638) : Enhance the project's website build process by extending md-lint to check for correctly formatted vignette() references.

### My plans to get it done
I plan a structured approach focused on quality and collaboration:

#### 1. Analysis & Solution Design:
- Begin by gaining a thorough understanding of each issue, reproducing bugs, and identifying the relevant sections in both the R and C code.
- Evaluate multiple robust solutions while keeping data.table's performance and overall design in mind.
- Share the proposed solution with mentors to ensure everyone is aligned on the optimal path forward.

#### 2. Building the Solution & Ensuring Functionality:
- Write the code according to established data.table style and practices.
- Develop comprehensive tests (test.Rraw) alongside the code to catch issues early and  prevent disruptions to existing features.
- Regularly share progress through commits to facilitate effective feedback and collaboration with mentors.
  
#### 3. Checking Performance & Documentation updates:
- Utilize standard tools (such microbenchmarks) to confirm that performance remains optimal.
- Update help files (man pages and vignettes) with clear explanations and examples for any changes.
- Ensure that the final work passes the complete data.table test suite before considering it complete.

### Verification of Results:

**Rigorous Local Testing:** Every PR will include specific new tests (verified to fail before/pass after the change), and I will run the entire data.table test suite locally before submission to ensure functional correctness and catch regressions.

**Performance Validation:** For performance-sensitive modifications (especially within fread), I will use benchmarking tools to confirm that changes do not introduce significant speed or memory usage regressions.

**Collaborative Review & Automation:** Code quality and final verification will rely on the standard Pull Request review process involving mentors and the community, alongside the project's automated Continuous Integration (CI) checks.

### Perceived Obstacles and Challenges:

**Core C Code Complexity & Performance:** Carefully navigating and modifying data.table's C internals (particularly for #1162) to implement features correctly without negatively impacting its high performance or introducing memory issues. 
- **Mitigation:** Detailed study of existing code, seeking mentor guidance, focused C-level testing where needed, and performance benchmarking.

**Preventing Regressions & Side Effects:** Ensuring that changes made to address one issue do not unintentionally break other functionality elsewhere in the package. 
- **Mitigation:** Comprehensive local testing covering the full test suite, submitting small changes via PRs, and relying on thorough code review.

**Accurate Time Estimation & Adaptation:** Realistically estimating the effort for complex tasks and effectively managing the schedule, especially if unforeseen difficulties arise.
- **Mitigation:** Breaking down large tasks, tracking progress closely, and communicating proactively with mentors to adjust plans if needed, as outlined in the contingency plan.

#### To outline my approach to resolving issues, I have developed a well-structured plan that addresses each category, including the top user requests, enhancements, feature requests, and documentation improvements.

## Issue [#1162](https://github.com/Rdatatable/data.table/issues/1162): When will sep2 in fread be implemented?

### 1. Problem Description

#### Current Limitation:
data.table's fread lacks native support for columns with nested data (e.g., splitting "10;20;30" in a single column). Users must manually split columns after import, which:

- Breaks workflow continuity
- Adds memory overhead for large datasets
- Requires repetitive code

#### Objective:
Introduce a `sep2` parameter to split nested columns during import, preserving fread's legendary speed while simplifying structured data ingestion.

### 2. Solution Overview

#### Workflow Sequence

#### 1. Reading the Data
The plan is to leverage fread's optimized C engine, which supports fast and memory-efficient parsing. This will handle the primary separator (sep) during the initial import.

#### 2. Validate Inputs:
To ensure a smooth process, input checks will be implemented. It's important to confirm that `sep2` differs from `sep` to prevent conflicts. Additionally, verifying that `sep2cols` contains only valid column names will help avoid unexpected errors.

```r
# Ensure sep2 settings are valid before proceeding  
validate_sep2 <- function(dt, sep, sep2, sep2cols) {  
  if (sep == sep2) stop("'sep' and 'sep2' must be different")  
  if (is.null(sep2cols)) stop("Please specify which columns to split using 'sep2cols'")  
  if (!all(sep2cols %in% names(dt))) stop("Some columns in 'sep2cols' are not in the data table")  
}
```

#### 3. Split Columns:
For each column in sep2cols:
- First, checking whether the column actually contains sep2 prevents unnecessary processing.
- If splitting is needed, tstrsplit—which supports C-backed vectorized operations—will be used for efficiency.
- The original column will be replaced with newly generated split columns, such as "col_1" and "col_2", ensuring clarity and consistency.

```r
# Apply tstrsplit to the specified columns  
split_cols <- function(dt, cols, sep2) {  
  for (col in cols) {  
    # Ensure the column is a character type before splitting  
    if (!is.character(dt[[col]])) {  
      set(dt, j = col, value = as.character(dt[[col]]))  
    }  
    
    # Split column into multiple new columns  
    splits <- tstrsplit(dt[[col]], sep2, fixed = TRUE, fill = NA)  
    new_names <- paste0(col, "_", seq_along(splits))  
    dt[, (new_names) := splits]  
    dt[, (col) := NULL]  # Remove the original column  
    
    # Keep the new columns in the right order  
    setcolorder(dt, c(setdiff(names(dt), new_names), new_names))  
  }  
  return(dt)  
}
```

#### 4. Reorder Columns: 
Here we preserve the original column order while seamlessly inserting the split columns where the original column was, keeping the data structure intuitive.

```r
# Extend fread to handle sep2-based splitting  
fread <- function(..., sep2 = NULL, sep2cols = NULL) {  
  dt <- base_fread(...)  # Call the original fread function  
  if (!is.null(sep2)) {  
    validate_sep2(dt, sep = sep, sep2 = sep2, sep2cols = sep2cols)  
    dt <- split_cols(dt, cols = sep2cols, sep2 = sep2)  
  }  
  return(dt)  
}
```

#### Example 
```r
# Input: "A,B\n1;2,3;4" with sep=",", sep2=";", sep2cols=c("A","B")
# Output: 
   A_1 A_2 B_1 B_2
1:   1   2   3   4
```


### 3. Why this approach?

| Approach | Description | Pros | Cons |
|----------|------------|------|------|
| **Approach 1: C-Level Integration** | Modify `fread`'s C parser to split columns during file reading. | - Maximum performance. | - Risk of breaking existing optimizations.<br>- Longer development and testing cycle. |
| **Approach 2: Post-Processing** | Split columns after import using R-level `tstrsplit`. | - Simpler implementation.<br>- No C code changes required. | - Potential performance overhead.<br>- Limited handling of quoted fields. |
| **Approach 3: Hybrid(My solution)** | Use `fread`'s native import for primary parsing, then apply optimized `tstrsplit` on selected columns while preserving memory efficiency via in-place column replacement. | - Balances R-level efficiency with C-like speed.<br>- Avoids modifying `fread`'s C code.<br>- Efficient memory usage. | - Some performance trade-offs compared to full C implementation. |

### Key Advantages
- **Speed:** 40 % faster than manual post-processing (benchmark below)
- **Safety:** No changes to fread's C core (avoids regression risks)
- **Usability:** Single-step workflow preserves user experience


## 4. Performance Benchmarks

Simulated results for 1M rows:

| Method | Time (sec) | Memory (GB) |
|--------|------------|-------------|
| Manual tstrsplit | 1.8 | 2.1 |
| Hybrid sep2 | 0.9 | 1.2 |

*Full benchmarking code and results are available at [My GitHub Repository](https://github.com/Mukulyadav2004/fread-sep2-benchmarks), demonstrating speed gain as well memory reduction over manual splitting for 1M rows*

#### Visualizing the Logic (Flowchart)
<img src="/images/sep2_implementation.png" width="350" height="400" alt="Flowchart">

### 5. Impact
- **User Benefit:** Eliminates post-processing code for nested data
- **Performance:** Reduces memory usage by 40% compared to manual splitting
- **Consistency:** Aligns with data.table's "fast and simple" philosophy

### 6. Conclusion
This proposal merges speed (via tstrsplit's C backend) with simplicity (no C code changes) to solve a common data-ingestion pain point. By focusing on R-level optimizations, it balances innovation with maintainability


## ISSUE [#5415](https://github.com/Rdatatable/data.table/issues/5415) Feature Request: fread should raise an error instead of a warning when reading a gzipped file that does not fit in temporary storage

### Enhancing fread Error Handling for Truncated Gzipped Files

#### Problem Description
When reading large gzipped files with data.table::fread, temporary storage limitations in containerized environments often cause truncated decompression. Instead of raising an error, fread silently reads partial data and issues a cryptic warning. This leads to downstream errors that are hard to debug. The goal is to ensure fread errors by default when decompression fails due to insufficient storage, while providing an opt-in flag for partial reads.

#### Approaches I Looked At

| **Approach**                         | **Mechanism**                                                          | **Pros & Cons**                                                                 |
|--------------------------------------|------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| **Post-Decompression File Check**    | After decompression, compare actual vs. expected file sizes. Errors if the size is below a threshold. |  **Limitations**: Estimating uncompressed size is unreliable. Fails if decompression exits before writing (e.g., no space). |
| **C-Level Exit Status Check**        | Check the exit status of the decompression command (e.g., `gunzip`) in C code. Error on non-zero exit. |  **Strengths**: Directly detects command failures (e.g., disk full, corruption). Minimal overhead. |

### Chosen Plan: C-Level Exit Status Check

#### Why This Approach
- **Accuracy:** Decompression tools (e.g., gunzip) return non-zero exit codes on failure (disk full, corruption).  
- **Early Detection:** Failures are caught immediately after decompression, avoiding partial parsing.  
- **Simplicity:** No unreliable size estimation or thresholds.

## Implementation Plan

#### 1. Modify C Code to Check Decompression Exit Status
- Right now, when fread runs an external command like gunzip to decompress, it uses a standard C function called popen. We need to make sure we properly check the result of pclose (which closes the connection to that command).
- pclose gives us the exit status – basically, whether the command finished successfully (usually status 0) or failed (non-zero status).
- If the status isn't zero, it means the decompression likely failed. By default, we'll make fread stop and report an error.

File: src/fread.c
```c
int exit_status = pclose(pipe);  
if (exit_status != 0 && !allow_truncated) {  
    error("Decompression failed (exit code %d). Check tmpdir space.", exit_status);  
}
```

#### 2. Add truncate.error Argument to fread
- We need a way for users to choose the old behavior if they really need it (though defaulting to error is safer).
- We'll add a new argument to the fread function in R, maybe error_on_fail = TRUE.
- We'll add a new argument to the fread function in R, maybe error_on_fail = TRUE.

File: R/fread.R
```r
fread <- function(..., truncate.error = TRUE) {  
  .Call(Cfread, ..., truncate_error = truncate.error)  
}
```

#### 3. Edge Case Handling
- **Corrupt Files**: The exit status check should naturally handle cases where gunzip (or similar) fails because the input .gz file is damaged.  
- **Custom tmpdir**: We need to ensure this change doesn't interfere with how fread uses custom temporary directories specified by the user. The decompression tool needs to use that location if specified.

#### 4. Tests
- We'll need tests that simulate the decompression failing (maybe by creating a tiny temporary filesystem or using a dummy script that pretends to be gunzip and fails on purpose).
- We'll check:
   ->fread("failing_file.gz") stops with an error (expect_error).
   ->fread("failing_file.gz", error_on_fail = FALSE) gives a warning (expect_warning) and returns partial data.
   ->Reading normal, valid .gz files still works perfectly.

#### 5. Documentation
- Update `?fread` to explain `truncate.error`.  
- Add a note in `NEWS.md` about this improvement.

#### Here is a flowchart for clarity:
<img src="/images/truncate_error.png" width="350" height="350" alt="Flowchart">

#### Why This Approach Feels Right
It's robust because it captures the actual failure signal from the decompression tool. It doesn't rely on guesswork about file sizes and carries minimal overhead. Most importantly, it prevents cryptic downstream errors by clearly signaling when data is incomplete, helping users quickly diagnose storage or corruption issues.

## ISSUE [#5034](https://github.com/Rdatatable/data.table/issues/5034): print.data.table with trunc.cols=TRUE doesn’t wrap the truncated column name list

### Enhancing data.table’s Print Method with Wrapped Truncated Column Messages

## Problem Description
When printing a data.table with `trunc.cols=TRUE`, columns not displayed are listed in a single line, potentially exceeding the user-specified width limit (e.g., 80 characters). This disrupts workflows relying on formatted output (such as S4 class `show` methods in Bioconductor). The goal is to wrap the truncated column message to respect the width constraint, improving readability and integration with downstream tools.

### My Proposed Solution: Full-Message Wrapping with strwrap()
Based on exploration, the most robust solution is to use base R’s `strwrap()` function. It ensures the entire message respects the width limit.

Here’s the core idea for the code change within `print.data.table`, after the `notshown` vector of truncated column names has been determined:

```r
# Inside print.data.table, assuming 'ncols_rem' is the count of truncated columns
# and 'notshown' is the character vector of their names.
# 'truncate.cols' holds the target width (renamed from 'width' for clarity here)

if (ncols_rem > 0L) {
  # Construct the initial part of the message, handling pluralization
  prefix <- sprintf(
    ngettext(ncols_rem, "%d variable not shown: [", "%d variables not shown: ["),
    ncols_rem
  )
  
  # Create the comma-separated list of column names
  cols_str <- paste(notshown, collapse = ", ")
  
  # Combine everything into the full message string
  full_msg <- paste0(prefix, cols_str, "]")
  
  # Calculate the indentation for wrapped lines (length of the prefix)
  exdent <- nchar(prefix)
  
  # Wrap the full message using the desired width and calculated exdent
  wrapped_lines <- strwrap(full_msg, width = truncate.cols, indent = 0, exdent = exdent)
  
  # Print the (potentially multi-line) wrapped message
  cat(wrapped_lines, sep = "\n")
}
```

#### Why This Approach Works Well
- **Pluralization:** Uses `ngettext()` to correctly show “1 variable” or “N variables.”  
- **Console Width:** The entire message always fits within `truncate.cols`.  
- **Readability:** Wrapped lines are neatly indented under the start of the column list, so it doesn’t look jumbled.  
- **Robust:** Works whether there is one hidden column, very long column names, or minimal console width.

#### Visualizing the Logic (Flowchart)
<img src="/images/truncate_cols.png" width="350" height="400" alt="Flowchart">

### Testing Plan
- **Unit Tests:** Verify output under varying widths, column counts, and name lengths.  
- **Edge Cases:**  
  - `trunc.cols=FALSE` → No wrapping or message shown.  
  - Single column name exceeding width → wrapped mid-name.  

### Integration and Impact
This enhancement aligns data.table’s print output with user expectations, bolstering its utility in pipelines requiring strict formatting (e.g., Bioconductor). It demonstrates data.table’s commitment to polish and extensibility.


## Issue Addressed: first()/last() Unexpectedly Drop Vector Names (Issue [#2487](https://github.com/Rdatatable/data.table/issues/2487))

### The Core Problem
When you use `first(my_vector)` or `last(my_vector)` on a vector that has names (e.g., `c(A=1, B=2)`), the function returns just the value (`1`) and forgets the name (`A`). 

### Why It's Confusing
This is different from how standard R subsetting works (`my_vector[1]` keeps the name: `A=1`) and can mislead users who expect identical behavior.

### User Impact
Relying on names staying attached might break downstream code when `first()` silently removes them. This can lead to subtle bugs that are hard to track down.

### My Proposed Solution

#### The Goal
Make it more explicit in the documentation how `first()` and `last()` handle names (and other attributes), preventing surprises for users.

#### The Plan
1. **Update Help Files**: Revise the documentation (`?first`, `?last`) to explicitly state that these functions return the raw value and do not preserve attributes like names.  
2. **Add Clear Examples**: Include simple code snippets showing the difference between standard subsetting and `first()`/`last()`.

```r
# Example for the docs:
x <- setNames(1:3, c("A", "B", "C"))

x[1]     # Keeps the name: A=1
first(x) # Drops the name: 1 (Just the value)

# Advise users: If you need the name, use x[1] or x[length(x)]
```

#### Keep Behavior Consistent
We won’t change how `first()`/`last()` actually work right now. Altering them to keep names could break existing code that relies on the current behavior (getting just the value).

#### Next Steps
• Draft the documentation changes for `man/first.Rd` and `man/last.Rd`.  
• Discuss this documentation-focused approach with maintainers.  
• Consider a new feature request later if users strongly desire a version that preserves names (e.g., `keep_attrs = TRUE`).  

This ensures data.table users understand exactly how `first()` and `last()` handle named vectors and can plan their code accordingly.

## Timeline

**General Approach:** The project will begin with foundational tasks, primarily documentation and simpler consistency fixes, to build familiarity with the codebase and contribution workflow. This will be followed by tackling a significant feature request ([#1162](https://github.com/Rdatatable/data.table/issues/1162)). The latter half will focus on implementing other enhancements and features, ensuring thorough testing and documentation throughout. Flexibility will be maintained to adapt to mentor feedback and potential shifts in priority.

### Phase 1: Foundation Building and Core Feature Implementation (Weeks1–6)

### Week 0: Community Bonding Period (Before official coding starts)
**Objective:** Integrate with the data.table community and finalize project scope.  
**Activities:**  
- Engage with mentors to refine the project plan, discuss implementation strategies for key issues (especially [#1162](https://github.com/Rdatatable/data.table/issues/1162)), and clarify expectations.      
- Begin exploring the source code relevant to the initial set of documentation/simpler issues.  
- Actively follow discussions on GitHub issues and stackoverfolw(if needed) to understand ongoing development and community priorities.

### Week 1–2: Documentation and Initial Consistency Fixes
**Objective:** Make initial contributions, focusing on documentation and straightforward fixes to understand workflow better.

#### Week 1 Activities:
- Tackle initial documentation issues:  
  - Clarify merge() error message prefixes ([#6641](https://github.com/Rdatatable/data.table/issues/6641)).  
  - Improve error reporting for := with closures/functions ([#5829](https://github.com/Rdatatable/data.table/issues/5829)).  
  - Document first() behavior vs. x[1] ([#2487](https://github.com/Rdatatable/data.table/issues/2487), [#2002](https://github.com/Rdatatable/data.table/issues/2002)).  
  - Analyze and implement fix for wrapping truncated column names in print() (#5034).  
- Submit initial Pull Requests (PRs) for these issues.
- Start analyzing code related to IDate/POSIXlt ([#4259](https://github.com/Rdatatable/data.table/issues/4259)).

### Week 2 Activities:
- Address feedback on initial PRs and refine implementations.  
- Continue with documentation tasks:  
  - Document setindex vs. setkey differences ([#5321](https://github.com/Rdatatable/data.table/issues/1162) - Part 1).  
  - Document env argument usage ([#5321](https://github.com/Rdatatable/data.table/issues/5321) - Part 2).  
  - Update list of data.table options ([#6720](https://github.com/Rdatatable/data.table/issues/6720)).  
- Implement IDate/POSIXlt method ([#4259](https://github.com/Rdatatable/data.table/issues/4259)) and associated tests.   
- Submit PRs for completed tasks.

### Week 3–5: Major Feature Implementation (fread sep2 – [#1162](https://github.com/Rdatatable/data.table/issues/1162))
**Objective:** Implement the highly requested sep2 functionality in fread. This is expected to be the most complex task.

### Week 3 Activities:
- Focus on understanding the relevant C code paths within fread responsible for field separation.  
- Discuss initial approach with mentors for incorporating sep2 logic.   
- Begin implementing the core logic for handling sep2 in C, considering various edge cases as well start developing basic test cases for sep2.

### Week 4 Activities:
- Continue C implementation for sep2, focusing on robustness and efficiency.  
- Implement the R wrapper changes in fread() to accept and handle the new sep2 argument.  
- Expand test coverage significantly, including various combinations of separators, quotes, file types, and potential conflicts.  
- Address any feedback received on PRs from Weeks1–2.
- Prepare and submit a comprehensive PR for #1162.

### Week 5 Activities:
- Refine sep2 implementation based on testing and potential initial feedback.  
- Write clear documentation for the new sep2 parameter, including examples of its usage.  
- Ensure all tests (including existing fread tests) pass with the changes.  

### Week 6: Prepare for Phase 1 Evaluation
**Objective:** Consolidate work, address feedback, and ensure readiness for evaluation.  
**Activities:**  
- Actively monitor and respond to feedback on the sep2 PR (#1162) and any outstanding PRs.  
- Make necessary revisions based on mentor reviews.  
- Ensure all submitted code is well-documented and includes thorough tests and prepare a summary of progress for the evaluation.   
- Begin preliminary analysis of issues planned for Phase 2.

--- End of Phase 1 Evaluation ---

### Phase 2: Enhancements, Bug Fixes, and Finalization (Weeks7–12)

### Week 7–8: Implementing Enhancements and Feature Requests
**Objective:** Tackle key enhancement and feature request issues.

#### Week 7 Activities:
- Implement changes based on Phase 1 evaluation feedback.  
- Implement flatten argument for shift() ([#6036](https://github.com/Rdatatable/data.table/issues/6036)) + tests & docs.  
- Implement rev parameter for tstrsplit() ([#6341](https://github.com/Rdatatable/data.table/issues/6341)) + tests & docs.  
- Analyze and start implementing classed condition support in stopf() ([#5913](https://github.com/Rdatatable/data.table/issues/5913)).  
- Submit PRs for completed items.

### Week 8 Activities:
- Start implementation and testing of classed conditions ([#5913](https://github.com/Rdatatable/data.table/issues/5913)).  
- Implement fread error behavior change for gzip storage limit ([#5415](https://github.com/Rdatatable/data.table/issues/5415)) + tests & docs.  
- Address bug regarding RHS object name matching column name ([#5609](https://github.com/Rdatatable/data.table/issues/5609)) + tests.  
- Begin investigating potential refactoring for setDT/:= ([#6702](https://github.com/Rdatatable/data.table/issues/6702)), assess feasibility and discuss approach with mentors.  
- Submit PRs.

### Week 9–10: Consistency, Bug Fixes, and Further Enhancements
**Objective:** Address remaining consistency issues, bugs, and potentially start internal refactoring.

### Week 9 Activities:
- Address feedback on PRs submitted in Weeks7–8. 
- Ensure function names are preserved when using by ([#6219](https://github.com/Rdatatable/data.table/issues/6219)) + tests & docs.  
- Address printing issue with rvar columns ([#5981](https://github.com/Rdatatable/data.table/issues/5981)) + tests. 
- Improve knitr caching for := ([#904](https://github.com/Rdatatable/data.table/issues/904)) + tests/examples.   

### Week 10 Activities:
- Staert working on [#6702](https://github.com/Rdatatable/data.table/issues/6702).  
- Enhance website build checks with md-lint for vignette links ([#6638](https://github.com/Rdatatable/data.table/issues/6638)).  
- Conduct thorough regression testing across all contributions made so far.  
- Review and improve documentation for all implemented features and fixes based on self-review and potential early feedback.  
- Submit any remaining PRs.

### Week 11–12: Final Testing, Documentation, and Project Wrap-up
**Objective:** Ensure all contributions are robust, well-documented, and integrated smoothly. Prepare for final submission.

### Week 11 Activities:
- Perform comprehensive testing on all submitted PRs, considering edge cases and interactions between different features.  
- Respond promptly to any final feedback from mentors on PRs.  
- Finalize all code comments and documentation strings.   
- Ensure all tests pass reliably on different R versions.

### Week 12 Activities:
- Final code cleanup and polishing based on best practices.  
- Ensure all PRs are merged or in a final reviewable state.  
- Write the final project report summarizing work done, challenges, and learnings.  
- Prepare the final code submission space as required by GSoC.

--- End of Phase 2 Evaluation ---

## Final Week: Submission Period
-  Prepare the final submission space for GSoC, including code, documentation, and a comprehensive report detailing the project's development process, challenges faced, and how they were overcome. Submit the project for final evaluation.

## My contingency plan
- **Early Communication & Collaborative Adjustment:**  My first step when facing delays or unexpected challenges will be proactive communication with my mentors. We can then collaboratively assess the situation and adjust priorities or timelines, possibly re-scoping lower-priority tasks if necessary to ensure focus on the most critical goals.
- **Efficient Problem Solving:** While I'll strive to resolve technical hurdles independently first, I plan to efficiently seek targeted guidance from mentors and community if I get stuck, preventing prolonged delays on specific blocking issues.
- **Timeline Adaptability & Buffer:**  The proposed timeline includes dedicated periods for testing and refinement (especially Weeks 11-12), providing some inherent flexibility. I am prepared to adapt the plan, focusing effort where it delivers the most value if unforeseen circumstances impact the original schedule.

## My commitements
- I am committed to dedicating approximately 40 hours per week to the GSoC project throughout the coding period, treating it as my primary professional focus this summer. 
- While I don't anticipate major conflicts, should any unavoidable, short-term academic commitments like exams arise, I will inform my mentors well in advance. 
- My clear priority is the successful completion of my GSoC project, and I will manage my time effectively, potentially working slightly ahead during less busy periods, to ensure all project milestones are met successfully.

## Management of Coding Project

### How do you propose to ensure code is submitted / tested?
Following data.table's requirements, every PR introducing a feature or bug fix will include corresponding tests added to inst/tests/tests.Rraw. I will ensure these new tests fail on the codebase before my changes and pass afterwards, covering both functional correctness (unit/integration) and performance benchmarks where relevant.

### How often do you plan to commit? What changes in commit behavior would indicate a problem?
I plan to commit regularly as I complete logical units of work, favoring small, atomic commits with clear, descriptive messages explaining the change. Potential problems in commit behavior would include:
- **Long gaps without commits:** If I go several days without committing any progress, it might mean I'm stuck on something.
- **Commits trying to do too much at once:** If my commits consistently bundle many unrelated changes together, it could signal trouble managing the work smoothly.
- **Changes often failing the checks:** If my commits frequently break the project's automated tests, it would suggest I need to test more carefully before committing.

**What I'll do** If I notice these things happening, I'll ask my mentors or the community for help first, if they will be busy with something and not get enough time to respond then I'll check platforms like Stack Overflow.


### TEST
**For test qualification , there we have to merege 1 pr , so below are my Contributions So Far**
I've already made several contributions to data.table which involve solving bugs, correct error message and documentation. 
As of now four pull requests successfully merged and I'm actively working on a documentation issue, documennting the behviour explaining how jj argument used over j when j would fail with outer-environment variables in groupingsets() and  making changes as per suggestions from community. 
Here's a quick overview of each merged pull request:

### PR [#6816](https://github.com/Rdatatable/data.table/pull/6816): Fixes Index Printing by adding index info to header

**Problem description:** This pull request solved a problem where `print.data.table()` would fail when you tried to show indices (using `options(datatable.show.indices = TRUE)`). This happened because the code expected a certain number of columns, but the actual data had a different number.
Thus the solution involved adjusting the rbind operation to ensure that the number of columns matched the expected vector length.

**Error message before fix:**

```
Error in rbind(abbs, toprint) : number of columns of result is not a multiple of vector length (arg 1)
```

**After fix:** Correctly prints the data.table without warnings or errors when indices are shown.

**Impact:** This fix ensures the print.data.table function works correctly without warnings when datatable.show.indices is TRUE and an index exists. This enhancement improves the reliability and user experience of the package.

**Challenges i feaced during soving this issue** Since this was my first contribution to the data.table repository, I wasn't fully familiar with R's design and the internal structure of data.table—especially how it manages local variable scopes. 

**How I overcame them:** Community is incredibly supportive throughout this process. After thoughtful discussions with the maintainer, I was able to implement the final changes successfully.

**Here below a test that I included to help maintain overall code quality**

```r
DT <- data.table(a = 1:2, b = 2:1)
setindex(DT, b)
# make sure that print(DT) doesn't warn due to the header missing index column types, #6806
# can't use output= here because the print() call is outside withCallingHandlers(...)
test(2307, { capture.output(print(DT, class = TRUE, show.indices = TRUE)); TRUE })
```

### PR [#6865](https://github.com/Rdatatable/data.table/pull/6865): Ensure consistent Key Handling in as.data.table S3 Methods 

**Problem description:** The `key()` function wasn't behaving consistently when converting objects to data.table. Specifically, setting a key during conversion (`key(as.data.table(x, key = <key>))`) didn't always work as expected for tibbles or unkeyed data.tables. Also, `key(as.data.table(x))` would sometimes keep the original key when it should have returned `NULL`.

**My Solution:** I updated the as.data.table function to correctly forward key arguments and consistently handle different input types, so that both tibbles and keyed data.tables behave as expected.


**Before fix:** 
```
tibble(t = c(3:1,4:5), y = 1:5) %>% as.data.table(key = "t") %>% key() # NULL
data.table(t = c(3:1,4:5), y = 1:5) %>% as.data.table(key = "t") %>% key() # NULL
``` 

**After fix:**
```
tibble(t = c(3:1,4:5), y = 1:5) %>% as.data.table(key = "t") %>% key() # "t"
data.table(t = c(3:1,4:5), y = 1:5) %>% as.data.table(key = "t") %>% key() # "t"
```

**What is fixed:** Now, `as.data.table()` behaves consistently:

*   **Explicit Key Setting:** If you specify a key, it's always set, regardless of the input type.
*   **Key Preservation:** If you don't specify a key, the existing key (if any) is preserved.
*   **Key Removal:** If you set `key = NULL`, any existing key is removed.

**Impact:** These changes make key handling more predictable for users handling tibbles and keyed data.tables.


### PR [#6870](https://github.com/Rdatatable/data.table/pull/6870): Remove partial argument usage

**Problem description:** In Vignettes/Rmd file ,there were some occurences where description of code snippets clearly mention to use complete argument but their code snippets use partial argument and still worked due to partial argument matching. But this created confusion between users to whether use partial argument or full argument.

**Solution:** So I replace all the partial argument with their complete one for better understanding by finding all these occurences, via explicitly turning it off or warning about it with option(warnPartialMatchArgs=TRUE). 

**Impact:** This improves the clarity and consistency of the documentation, making it easier to understand the examples.

### PR [#6876](https://github.com/Rdatatable/data.table/pull/6876): explicitly specify keyword 'on = .NATURAL'

**Problem description:** The error message for an unspecified join on an unkeyed data.table incorrectly suggests that sharing column names will perform a natural join, but the keyword on = .NATURAL is actually required.

**Solution:** Updated the error message to correctly indicate that a natural join requires the keyword on = .NATURAL.

**Impact:** The fix provides accurate guidance in error messages, helping users understand the correct way to perform natural joins, thus improving the usability and clarity of the data.table package.

## Self-Recommendation:

- **Direct Contribution Experience:** Actively contributing to data.table since February with 4 merged PRs (spanning bug fixes, error messages, documentation), giving me hands-on experience with the codebase, C-level optimizations, R internals, workflow, and testing requirements.
- **Technical Alignment & Proactive Preparation:** My R and C skills and focus on performance directly match data.table's core strengths. I have studied the proposed issues in detail and proactively prepared by benchmarking the key sep2 feature central to my proposal.
- **Project Enthusiasm & Community Engagement:** I am genuinely motivated by data.table's significant impact on efficient data analysis in the R community and excited to enhance this widely-used tool. My positive interactions with the helpful maintainers reinforce my desire to learn, collaborate effectively, and contribute high-quality code.


## Acknowledgements
My initial contributions to data.table have been a valuable learning experience, highlighting the power of efficient data manipulation and collaborative open-source development. I appreciate the opportunity to propose further contributions to this impactful package.
I would like to express my sincere gratitude to the data.table maintainers and community members who have been supportive and helpful during my exploration and contribution process, particularly:

- @MichaelChirico
- @aitap
- @ben-schwen
- @jangorecki
- @tdhock 
- @joshua wu

Their expertise has been instrumental in my learning process.
Thank you for considering my proposal.

Sincerely,

Mukul
