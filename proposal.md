# R PROJECT FOR STATISTICAL COMPUTING

## MUKUL KUMAR  27/03/2025
**mukulyadav6446@gmail.com**

**+91 8708206446**

**ARMY INSTITUTE OF TECHNOLOGY  ELECTRONICS AND TELECOMMUNICATION**

**INDIA/GMT +5:30**

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
- My motivation
- Scheduled conflicts
- Mentors
- Coding Plan And Methods
- Timeline
- Management of coding project
- Test
- Miscellaneous

## Project title
**Enhancing Data.Table: Enhancing Functionality, and Ensuring Quality**

## Project description
This project aims to enhance data.table by improving functionality, optimizing performance, and refining documentation. It includes adding new features, clarifying advanced concepts, optimizing algorithms, and strengthening test coverage. These improvements will make data.table more efficient, user-friendly, and accessible to the R community.

## Project idea page
https://github.com/rstats-gsoc/gsoc2025/wiki/data.table

## ABOUT ME

I am Mukul Kumar, a second-year student of B.E. Electronics and Telecommunication Engineering at the Army Institute of Technology, Pune. My early interest in solving puzzles sparked a passion for problem-solving and competitive programming, which led me to explore various technical fields such as machine learning and data science. Discovering machine learning felt like unlocking a superpower—teaching computers to learn and predict. My growing interest in data manipulation and system efficiency brought me to the data.table project, where I've been contributing since February 2025. Working with data.table's codebase has given me hands-on experience with R internals, low-level C programming, and improving performance for large datasets.

I have successfully merged 4 pull requests that addressed key issues such as fixing partial matching in vignettes, enhancing documentation, and resolving bugs related to coercion and index handling. Each contribution has not only strengthened my technical knowledge but also deepened my understanding of the complexities involved in maintaining a widely-used open-source project.

Currently, I am working on resolving an issue involving print.data.table() where both a key and an index are set. This task requires debugging low-level C code and optimizing type coercion to maintain high performance. It has given me the opportunity to dive deeper into the internals of data.table and refine my skills in C programming and performance optimization.

My proficiency in R, Python, C, and Java has enabled me to work on multiple projects and strengthen my knowledge of algorithms, data structures, and system optimization. One of my notable projects involved a data analysis task in R, where I analyzed large datasets related to customer behavior, identified patterns, and generated actionable insights. This project involved data cleaning, visualization using ggplot2, and implementing statistical models to improve decision-making processes.

I also serve as the Project Head of the Research and Development Club at my college, where I have successfully organized and managed large-scale events such as Fusion (intra-college event) and Avishkar (inter-college event). These experiences have enhanced my project management, communication, and problem-solving skills, helping me effectively balance technical expertise with leadership responsibilities.

I am excited about the opportunity to contribute further to the data.table project through Google Summer of Code (GSoC). I am fully committed to dedicating my full-time focus to this project during the summer. With no other internships or academic commitments, I am prepared to invest my complete effort in contributing meaningfully to the project, collaborating effectively with mentors and the community, and ensuring timely progress with high-quality deliverables.

## Contact Information
- Ph no: +91 8708206446
- Email: mukulyadav6446@gmail.com
- Github: Mukulyadav2004
- Name: MUKUL KUMAR
- Postal address: ARMY INSTITUTE OF TECHNOLOGY, PUNE, MAHARASHTRA, 411015 
- Telephone: +91 8708206446
- Email(s): mukulyadav6446@gmail.com (primary), mukulkumar_230467@aitpune.edu.in (secondary)

## Affiliation
- Institution: ARMY INSTITUTE OF TECHNOLOGY
- Program: BACHELORS OF ENGINEERING, ELECTRONICS AND TELECOMMUNICATION
- Stage of completion: 2ND YEAR
- Contact to verify: mukulkumar_230467@aitpune.edu.in (email address given by college)

## MY MOTIVATION

I'm confident I'd be a valuable contributor to this project. I'm passionate about learning and have hands-on experience, and I'm genuinely curious about how complex systems work. Since February 2025, I've been contributing to data.table, and each pull request feels like a rewarding challenge. Fixing issues and improving documentation has deepened my understanding of its internals, from efficient data handling to clever C-level optimizations.

What excites me most about data.table is its ability to process massive datasets with impressive speed. Improving data.table isn't just about fixing bugs for me; it's about helping the data science community by making data processing more efficient, leading to faster insights and better models.

Being part of the data.table community has been a great experience. The people are always ready to help, and every interaction has taught me something new, from understanding C code related to `setkey` to learning about R's memory management. This supportive environment motivates me to keep contributing and learning more.

I'm also excited about the challenge of working on a large and complex codebase like data.table. Understanding and contributing to such a widely used open-source project pushes me to improve my technical skills while being part of a such a suppportive community that values performance and efficiency. I'm eager to keep refining data.table and make it even better for the broader data science and analytics community.

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

### About my project 
This project is all about making the data.table package for the R programming language even better. data.table is a super-fast and efficient way to work with data, and all I need is to fix some existing issues, add new features that people have asked for, improve the documentation, and make the way data is displayed cleaner. This will help everyone who uses data.table to work with their data more easily and effectively.

## Proposed Goals for the Project
My primary goal for this Google Summer of Code project is to make tangible contributions to the data.table package, focusing on areas that enhance its functionality, improve consistency, and enrich the user experience through clearer documentation and error handling.

I have carefully selected a range of issues, spanning feature additions, bug fixes, and documentation improvements, that I believe align well with the project's objectives and my skills. While this list represents my initial plan, I am fully prepared to adapt and prioritize based on mentor feedback and the evolving needs of the project throughout the summer. 

My aim is to deliver high-quality, well-tested code and documentation that benefits the wide data.table user community.

## Key Areas of Focus and Planned Contributions

I've grouped the issues I plan to address into three main categories:

### 1. Extending Functionality and Performance
This group focuses on adding new features and enhancing existing functions to make data.table even more powerful and versatile for data manipulation tasks.

**fread Enhancements:**
- #1162 : Implement the popular sep2 feature to provide more flexibility when reading files with potentially irregular separator patterns.
- #5415 : Improve robustness by making fread raise an error (instead of just a warning) when a gzipped file decompression exceeds available temporary storage, preventing unexpected behavior downstream.

**New Function Arguments:**
- #6036 : Add a flatten argument to shift(), giving users control over the output structure when shifting list columns.
- #6341 : Introduce a rev parameter to tstrsplit(), enabling more intuitive selection of elements from the end when splitting strings.

**Internal Improvements:**
- #5913 : Add support for classed conditions in internal messaging functions like stopf(), allowing for more structured error handling within the package.
- I#6702 : Refactor setDT and := to consolidate code related to assigning data.table objects, potentially improving maintainability and consistency.

### 2. Improving Consistency and Reliability
Addressing inconsistencies and bugs is crucial for a reliable user experience. This section targets issues that refine existing behaviors and fix specific problems.

**Consistent Behavior:**
- #6219 : Ensure function names are preserved within data.table calls when using the by argument , maintaining clarity in complex operations.
- #5034 : Align the printing behavior of truncated column lists with user expectations by enabling wrapping when trunc.cols=TRUE .
- #4259 : Standardize date/time handling by adding a POSIXlt method for IDate, improving interoperability.

**Bug Fixes & Error Handling:**
- #5609 : Resolve errors that occur when the object assigned on the right-hand side of := shares a name with an existing column .
- #5981 : Address printing issues for data.tables containing specific column types, such as rvar objects from the posterior package. 
- #904 : Enhance usability within environments like knitr by improving caching behavior for := assignments.

### 3. Enhancing User Experience through Documentation and Clarity
Clear documentation and informative error messages are vital for usability. This group focuses on making data.table easier to learn and troubleshoot.

**Clearer Error Messages & Warnings:**
- #6641 : Make merge() error messages less confusing by ensuring the 'x' and 'i' prefixes consistently refer to the correct input tables.
- #5829 : Improve error reporting or guidance when the right-hand side of := is a function or closure, helping users debug their code.

**Documentation Improvements:**
- #2487 : Explicitly document the behavior of first() with named vectors compared to standard subsetting x[1].
- #5321 : Clarify the differences in indexing behavior between setindex and setkey for non-character columns.
- #2002 : Clarify that first(x) does not always return the same result as x[1] in documentation.
- #6720 : Update documentation to provide a comprehensive, current list of data.table options and their values.
- #6638 : Enhance the project's website build process by extending md-lint to check for correctly formatted vignette() references.

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


#### To outline my approach to resolving issues, I have developed a well-structured plan that addresses each category, including the top user requests, enhancements, feature requests, and documentation improvements.

### 1. Issue #1636 in data.table
fread lacks native handling for numeric columns that include thousand separators (e.g., "12,345"). Users need to handle the task of removing or replacing specific separators (like commas used as thousand separators) from the data themselves, after the data has been initially processed or loaded. So in this I proposed to enhance fread so that large files with thousand separators can be read directly without additional preprocessing.

#### Summary of Approaches

| Approach                                 | Description                                                                 | Advantages                                                          | Disadvantages                                                       |
|------------------------------------------|----------------------------------------------------------------------------|---------------------------------------------------------------------|----------------------------------------------------------------------|
| **Post-Processing Outside of fread**     | Read columns as text, remove separators in R, and convert to numeric.     | No changes to C code; quick solution for small datasets.           | Extra processing time; inefficient for large data; less user-friendly. |
| **Minimal C Change (Inline Stripping)**  | Modify numeric parsing functions to remove thousand separators before conversion using `strtod`. | Simple approach with minimal code changes.                         | Frequent memory allocation may reduce performance, especially with multi-threading. |
| **Refined Production-Grade Implementation (Proposed)** | Pass a `thousands` argument from R to C, use thread-safe buffers to remove separators, then validate numbers. | Maintains performance by avoiding frequent memory allocations; handles edge cases carefully. | Requires more complex implementation and testing.                    |

My approach focuses on minimal overhead, using a reusable buffer per thread, while maintaining clarity in the code base:

In R/fread.R:
– Introduce a new argument thousands, accepting a single non-numeric character.
– Validate and pass it to the C layer via .Call.

In C (fread.h, freadR.c, coerce.c, read.c, init.c):
– Update global and thread-local structures to store the thousands separator.
– Create thread-specific buffers for removing separators.
– During numeric field detection (coerce.c), strip the separator once and parse using strtod
– In numeric parsing (read.c), similarly strip prior to calling strtod, returning NA if parsing fails.
– Similarly, strip and parse in read.c, marking invalid data as NA if parsing fails.
– Properly initialize and free these buffers to avoid memory leaks.

Example code snippets to illustrate approach:

```c
// src/fread.h
#ifndef DATA_TABLE_FREAD_H
#define DATA_TABLE_FREAD_H

typedef struct {
  char thousands_sep;      // declare thousands separator
  // ... other global field
} FreadGlobalArgs;

typedef struct {
  char *buffer;            // Reusable buffer for stripping separators
  size_t buffer_size;      // here it is current capacity of buffer
  // ... other thread-local fields
} FreadThreadLocal;
#endif
```

```r
// R/fread.R
fread <- function(..., thousands = NULL) {
  if (!is.null(thousands)) {
    if (nchar(thousands) != 1 || grepl("[0-9.eE+-]", thousands, perl = TRUE)) {
      stop("thousands must be a single non-numeric character.")
    }
    thousands <- as.character(thousands)
  }
  .Call("Cfread", ..., thousands = thousands, PACKAGE = "data.table")
}
```

```c
// src/coerce.c
static bool strip_separator(const char *s, int len, char sep, 
                            char **buf, size_t *buf_size) {
  if ((size_t)len + 1 > *buf_size) {
    char *temp = realloc(*buf, len + 1);
    if (!temp) return false;
    *buf = temp;
    *buf_size = len + 1;
  }
  int j = 0;
  for (int i = 0; i < len; i++) {
    if (s[i] != sep) {
      (*buf)[j++] = s[i];
    }
  }
  (*buf)[j] = '\0';
  return true;
}
bool is_ok_double(const char *s, int len, FreadThreadLocal *tl, char sep) {
  if (!s || len <= 0) return false;
  const char *target = s;
  if (sep != '\0') {
    if (!strip_separator(s, len, sep, &tl->buffer, &tl->buffer_size)) return false;
    target = tl->buffer;
    len = (int)strlen(tl->buffer);
  }
  char *end;
  (void)strtod(target, &end);
  return (end == target + len);
}
```

Key Refinements in This Approach: 
- Each thread has its own buffer, preventing data conflicts during parallel processing.
- Buffers are reused instead of repeatedly allocating and freeing memory.
- If strtod fails or doesn’t consume the entire string, invalid inputs are marked as NA.
- The thousands parameter is treated as a fixed character without relying on locale settings.

### 2. print.data.table with trunc.cols=TRUE doesn't wrap the truncated column name list #5034

#### Problem summary
When printing a large data.table with trunc.cols=TRUE, the output trims columns to fit within a line width (like 80 characters). But the list of hidden column names at the bottom doesn’t follow this rule. For example:

```r
# Current output (exceeds 80 characters):  
3 variables not shown: [fourth_long_column_name, fifth_long_column_name, sixth_long_column_name]
```

This can look broken in tools that rely on clean formatting (like Bioconductor packages or S4 classes).

#### Solution:
My approach is to make the hidden column list wrap neatly to match the line width.
Let me explain this step by step:

1. Find Where the Message is Built:
Inside the print.data.table function, there’s code that generates the "variables not shown" message. We need to tweak that part.

2. Wrap the Message Like a Paragraph:
Use R’s strwrap() function to split the message into multiple lines, just like wrapping text in a word processor. Instead of hardcoding width=80, we’ll use the same width setting the user chose for printing the table.

3. Print the Wrapped Lines:
Instead of printing the message in one long line, we’ll print each wrapped line separately.

#### Code changes in print.data.table.R:

```r
# Current code snippet
if (length(not_shown) > 0) {
  txt <- sprintf(
    "%d variable%s not shown: %s", 
    length(not_shown), 
    if (length(not_shown) > 1L) "s" else "", 
    brackify(not_shown)
  cat(txt, "\n", sep = "")
}
```

```r
# Proposed modification
if (length(not_shown) > 0) {
  txt <- sprintf(
    "%d variable%s not shown: %s", 
    length(not_shown), 
    if (length(not_shown) > 1L) "s" else "", 
    brackify(not_shown))
  # Apply line wrapping using available_width
  wrapped_txt <- strwrap(txt, width = available_width, exdent = 2)
  cat(wrapped_txt, sep = "\n")
}
```

In this strwrap() splits the message into lines that don’t exceed current_width (e.g., 80) and exdent=2 indents wrapped lines by 2 spaces for better readability.

#### Example Output
before modification

```r
3 variables not shown: [fourth_long_column_name, fifth_long_column_name, sixth_long_column_name]  
```

After modification

```r
3 variables not shown: [fourth_long_column_name,  
  fifth_long_column_name,  
  sixth_long_column_name]  
```

This maintain consistency and readability as the hidden column list now matches the rest of the table’s width and this also makes it easier for R package developers (e.g., Bioconductor) who use data.table internally.

### 3. first(named_vector) removes names #2487

#### Issue summary
The functions first() and last() from data.table behave differently from x[1] (or x[.N]) when extracting elements from a named vector or can say first(named_vector) removes names while x[1] retains them.

```r
library(data.table)
x = setNames(, "A")
x[1]
#>   A 
#> "A"
first(x)
#> [1] "A
```

In the snippet above, x[1] yields an element that retains the name (label_A), whereas first(x) returns only the raw value ("A") without the name
• The documentation currently implies first(x) can be used interchangeably with x[1], but first() strips attributes (including names), whereas x[1] preserves them. Users who rely on names or other attributes (e.g., for named indexing or downstream lookups) can be surprised by this behavior and may interpret the documentation incorrectly.

#### My approach
• So my approach is to clarify the documentation to specify exactly how first() treats attributes and provide users with explicit examples showing how names (and other attributes) may be lost, along with a recommended alternative (x[1]) while preserving the attributes. In short updating the documentation for first() and last() to highlight that these functions return raw values without preserving names or other attributes and adding examples to help users understand the difference between x[1] and first(x), with usage notes for typical scenarios involving named vectors or list elements.

So I'll update man/first.Rd and man/last.Rd to include the attribute behavior clarification and examples.
Examples code snippet 

```r
# Named vector behavior
x <- setNames(1:3, c("A", "B", "C"))
x[1]        # Returns named element: A 1
first(x)    # Returns unnamed: 1

# List behavior
y <- list(A = "a", B = "b")
y[1]        # Returns sublist: list(A = "a")
first(y)    # Returns first element: "a" (unnamed)
```

Discuss the issue with mentors and confirm the approach (documentation clarification) draft changes 
This helps new and existing users avoid confusion when dealing with named vectors.
If further improvements are requested (e.g., providing an option to preserve names in first()), it can be discussed in a separate enhancement issue to avoid unexpected breakage of existing code.

### 4. feature request: fread should raise an error instead of a warning when reading a gzipped file that does not fit in temporary storage #5415

#### Problem summary:
When fread() reads a gzipped file larger than the available temporary storage, it silently returns partial data and only issues a warning. This is dangerous in automated workflows (e.g., containers, batch jobs) because users might unknowingly process incomplete datasets, leading to confusing downstream errors.

# Current behavior (risky):

```r
dt <- fread("huge_file.gz")  # here warning: "File is truncated"
sum(dt$value)  # It returns incorrect result with no obvious error
```

This is important because as in automated setups like cron jobs or cloud pipelines, it's easy to miss warnings. This can make debugging much harder, as errors often show up much later and far away from where the problem actually started. Additionally, partial data isn’t very useful as most don’t want a random selection of rows that happen to fit into temporary storage.

#### Proposed Solution:
Modify fread() to error immediately if decompression fails due to:
 - Insufficient disk space in the temporary directory (tmpdir).
 - Corrupted gzip files or incomplete decompression.

#### Implementation Steps:
Check Decompression Exit Codes by Using system2() or R.utils to detect failures during decompression:

# Code snippet of implementation inside data.table's fread decompression logic:

```r
tmp_file <- tempfile(tmpdir = tmpdir)
status <- system2("gzip", c("-dc", shQuote(input_file)), stdout = tmp_file)
if (status != 0) {
  unlink(tmp_file)  # Clean up
  stop("Decompression failed (code ", status, "). Check disk space or file integrity.")
}
```

Validate Uncompressed Size for known file sizes (e.g., HTTP Content-Length header), compare against the decompressed file:

```r
expected_size <- get_expected_size()  # Pseudo-code for illustration
actual_size <- file.info(tmp_file)$size
if (!allow_truncated && actual_size < expected_size) {
  stop("Decompressed file is smaller than expected. Possible truncation.")
}
```

Add a Safety Valve argument to introduce allow_truncated_gzip = FALSE to let advanced users opt into the old behavior:

```r
fread("file.gz", allow_truncated_gzip = TRUE)  # Restores original warning behavior
```

Now to handle edge cases , I proposed scenerios along with their handlings
1. For corrupted gzip files error immediately (no partial reads)
2. For Tiny /tmp in containers clear error message suggesting tmpdir argument.
3. If legacy scripts needing partial reads use (allow_truncated_gzip = TRUE).

#### Example Workflow After Fix:

```r
tryCatch(
  {
    dt <- fread("huge_file.gz") 
  },
  error = function(e) {
    message("Tip: Use tmpdir='/mnt/large_storage' or check disk space.")
    stop(e)
  }
)
```

#### Update in documentation after fix:
- I'll add a note to ?fread about the new error behavior and allow_truncated_gzip.
- Will include troubleshooting tips for "disk full" errors in the tmpdir argument docs

## Timeline

**General Approach:** The project will begin with foundational tasks, primarily documentation and simpler consistency fixes, to build familiarity with the codebase and contribution workflow. This will be followed by tackling a significant feature request (#1162). The latter half will focus on implementing other enhancements and features, ensuring thorough testing and documentation throughout. Flexibility will be maintained to adapt to mentor feedback and potential shifts in priority.

### Phase 1: Foundation Building and Core Feature Implementation (Weeks 1–6)

#### Week 0: Community Bonding Period (Before official coding starts)
**Objective:** Integrate with the data.table community and finalize project scope.  
**Activities:**  
- Engage with mentors to refine the project plan, discuss implementation strategies for key issues (especially #1162), and clarify expectations.    
- Set up the complete local development environment, including R development tools and C compilation toolchain if necessary.  
- Begin exploring the source code relevant to the initial set of documentation/simpler issues.  
- Actively follow discussions on GitHub issues and stackoverfolw(if needed) to understand ongoing development and community priorities.

#### Week 1–2: Documentation and Initial Consistency Fixes
**Objective:** Make initial contributions, focusing on documentation and straightforward fixes to understand workflow better.

##### Week 1 Activities:
- Tackle initial documentation issues:  
  - Clarify merge() error message prefixes (#6641).  
  - Improve error reporting for := with closures/functions (#5829).  
  - Document first() behavior vs. x[1] (#2487, #2002).  
  - Analyze and implement fix for wrapping truncated column names in print() (#5034).  
- Submit initial Pull Requests (PRs) for these issues, carefully following contribution guidelines.  
- Start analyzing code related to IDate/POSIXlt (#4259).

##### Week 2 Activities:
- Address feedback on initial PRs and refine implementations.  
- Continue with documentation tasks:  
  - Document setindex vs. setkey differences (#5321 - Part 1).  
  - Document env argument usage (#5321 - Part 2).  
  - Update list of data.table options (#6720).  
- Implement IDate/POSIXlt method (#4259) and associated tests.  
- Begin deep dive into fread's architecture and C code in preparation for #1162 (sep2).  
- Submit PRs for completed tasks.

#### Week 3–5: Major Feature Implementation (fread sep2 – #1162)
**Objective:** Implement the highly requested sep2 functionality in fread. This is expected to be the most complex task.

##### Week 3 Activities:
- Focus on understanding the relevant C code paths within fread responsible for field separation.  
- Develop an initial design/approach for incorporating sep2 logic. Discuss with mentors.  
- Begin implementing the core logic for handling sep2 in C, considering various edge cases (e.g., quoted fields, empty fields, interaction with existing parameters).  
- Start developing basic test cases for sep2.

##### Week 4 Activities:
- Continue C implementation for sep2, focusing on robustness and efficiency.  
- Implement the R wrapper/interface changes in fread() to accept and handle the new sep2 argument.  
- Expand test coverage significantly, including various combinations of separators, quotes, file types, and potential conflicts.  
- Address any feedback received on PRs from Weeks 1–2.

##### Week 5 Activities:
- Refine sep2 implementation based on testing and potential initial feedback.  
- Write clear documentation for the new sep2 parameter, including examples of its usage.  
- Ensure all tests (including existing fread tests) pass with the changes.  
- Prepare and submit a comprehensive PR for #1162.

##### Week 6: Prepare for Phase 1 Evaluation
**Objective:** Consolidate work, address feedback, and ensure readiness for evaluation.  
**Activities:**  
- Actively monitor and respond to feedback on the sep2 PR (#1162) and any outstanding PRs.  
- Make necessary revisions based on mentor reviews.  
- Ensure all submitted code is well-documented and includes thorough tests.  
- Clean up local branches and prepare a summary of progress for the evaluation.  
- Begin preliminary analysis of issues planned for Phase 2.

--- End of Phase 1 Evaluation ---

### Phase 2: Enhancements, Bug Fixes, and Finalization (Weeks 7–12)

#### Week 7–8: Implementing Enhancements and Feature Requests
**Objective:** Tackle key enhancement and feature request issues.

##### Week 7 Activities:
- Implement changes based on Phase 1 evaluation feedback.  
- Implement flatten argument for shift() (#6036) + tests & docs.  
- Implement rev parameter for tstrsplit() (#6341) + tests & docs.  
- Analyze and start implementing classed condition support in stopf() (#5913).  
- Submit PRs for completed items.

##### Week 8 Activities:
- Complete implementation and testing for classed conditions (#5913).  
- Implement fread error behavior change for gzip storage limit (#5415) + tests & docs.  
- Address bug regarding RHS object name matching column name (#5609) + tests.  
- Begin investigating potential refactoring for setDT/:= (#6702), assess feasibility and discuss approach with mentors.  
- Submit PRs.

#### Week 9–10: Consistency, Bug Fixes, and Further Enhancements
**Objective:** Address remaining consistency issues, bugs, and potentially start internal refactoring.

##### Week 9 Activities:
- Ensure function names are preserved when using by (#6219) + tests & docs.  
- Address printing issue with rvar columns (#5981) + tests. 
- Improve knitr caching for := (#904) + tests/examples.  
- Address feedback on PRs submitted in Weeks 7–8.  
- If #6702 (refactoring) is deemed feasible and valuable, begin implementation. Otherwise, pick up another lower-priority issue or focus on extensive testing/documentation.

##### Week 10 Activities:
- Continue work on #6702 (if applicable) or focus on refining existing contributions.  
- Enhance website build checks with md-lint for vignette links (#6638).  
- Conduct thorough regression testing across all contributions made so far.  
- Review and improve documentation for all implemented features and fixes based on self-review and potential early feedback.  
- Submit any remaining PRs.

#### Week 11–12: Final Testing, Documentation, and Project Wrap-up
**Objective:** Ensure all contributions are robust, well-documented, and integrated smoothly. Prepare for final submission.

##### Week 11 Activities:
- Perform comprehensive testing on all submitted PRs, considering edge cases and interactions between different features.  
- Respond promptly to any final feedback from mentors on PRs.  
- Finalize all code comments and documentation strings.   
- Ensure all tests pass reliably on different R versions.

##### Week 12 Activities:
- Final code cleanup and polishing based on best practices.  
- Ensure all PRs are merged or in a final reviewable state.  
- Write the final project report summarizing work done, challenges, and learnings.  
- Prepare the final code submission space as required by GSoC.

--- End of Phase 2 Evaluation ---

### Final Week: Submission Period
-  Prepare the final submission space for GSoC, including code, documentation, and a comprehensive report detailing the project's development process, challenges faced, and how they were overcome. Submit the project for final evaluation.

## My contingency plan
- **Early Communication & Collaborative Adjustment:**  My first step when facing delays or unexpected challenges will be proactive communication with my mentors. We can then collaboratively assess the situation and adjust priorities or timelines, possibly re-scoping lower-priority tasks if necessary to ensure focus on the most critical goals.
- **Efficient Problem Solving:** While I'll strive to resolve technical hurdles independently first, I plan to efficiently seek targeted guidance from mentors or the community if I get stuck, preventing prolonged delays on specific blocking issues.
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
I've already made several contributions to data.table which involve solving bugs , correct error message and documentation. 
As of now four pull requests successfully merged and I'm actively working on a documentation issue , documennting the behviour explaining how jj argument used over j when j would fail with outer-environment variables in groupingsets() and  making changes as per suggestions from community. 
Here's a quick overview of each merged pull request:

### PR #6816: Fixes Index Printing by adding index info to header

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

### PR #6865: Ensure consistent Key Handling in as.data.table S3 Methods 

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


### PR #6870: Remove partial argument usage

**Problem description:** In Vignettes/Rmd file ,there were some occurences where description of code snippets clearly mention to use complete argument but their code snippets use partial argument and still worked due to partial argument matching. But this created confusion between users to whether use partial argument or full argument.

**Solution:** So I replace all the partial argument with their complete one for better understanding by finding all these occurences, via explicitly turning it off or warning about it with option(warnPartialMatchArgs=TRUE). 

**Impact:** This improves the clarity and consistency of the documentation, making it easier to understand the examples.

### PR #5455: explicitly specify keyword 'on = .NATURAL'

**Problem description:** The error message for an unspecified join on an unkeyed data.table incorrectly suggests that sharing column names will perform a natural join, but the keyword on = .NATURAL is actually required.

**Solution:** Updated the error message to correctly indicate that a natural join requires the keyword on = .NATURAL.

**Impact:** The fix provides accurate guidance in error messages, helping users understand the correct way to perform natural joins, thus improving the usability and clarity of the data.table package.



## Acknowledgements
My experience with data.table has provided valuable insights into efficient data manipulation and the importance of robust open-source tools. This project represents an opportunity to contribute directly to a package that significantly impacts the R community.
I express my sincere gratitude to the data.table maintainers and community, especially:
- @MichaelChirico
- @aitap
- @ben-schwen
- @jangorecki
- @tdhock (Toby Dylan Hocking)
- @joshua wu

Their expertise and contributions have been instrumental in my understanding of data.table.
Thank you for your consideration.
Sincerely,
Mukul

### Miscellaneous
## Questions for me:
This section is voluntary reading:

### Why choose this project?
As a student doing learning growing in machine learning era I believe that it is my job to present tools of advanced scientific computing and intelligence in the simplest format possible. The advances in Machine Learning/Deep Learning/Artificial Intelligence and other allied fields should be accessible to a wider array of people. Domain experts, academic scholars, teachers, mathematicians, statisticians, scientists and their like have more domain knowledge than computer programmers in their respective fields. They are therefore best suited to make approximations in different machine learning models and draw interesting inferences using exploratory data analysis. This is something that could never be achieved without a certain level of domain knowledge.
Expecting these people to learn the intricacies of programming is counter-intuitive, hence it’s in everyone’s best interest that they be able to carry out their tasks with ease and in the least possible time.
I would really love to be a part of a package that can enhance the data manipulation and fast reading of files enhance the productivity of analysed data.

### Do you consider yourself fit for the project?
Absolutely. I'm genuinely enthusiastic about contributing to the data.table package, and I believe my skills and dedication align perfectly with the project's goals. The prospect of enhancing a tool that significantly impacts the efficiency of countless R users is incredibly motivating.
My deep dive into the data.table codebase, coupled with my thorough research into the specific GitHub issues ([#1636, #6036, #5034, etc.]), has given me a solid understanding of the challenges and potential solutions. I'm committed to delivering well-tested, documented, and maintainable code that seamlessly integrates with the existing package.

Furthermore, my proactive approach to learning the data.table development workflow, setting up a robust development environment, and establishing clear communication channels with mentors will ensure a smooth and productive GSoC experience. I understand the importance of clear communication, and I'm ready to ask for feedback, and help, when needed.
While my experience with large open-source projects is still developing, my consistent work on personal and academic projects has solidified my Git and GitHub proficiency. I am comfortable with collaborative development, and I am ready to adhere to the data.table contribution guidelines.
I am confident that my passion for efficient code, my dedication to thorough research and testing, and my commitment to clear communication will allow me to make valuable contributions to the data.table project. I'm eager to learn from the experienced maintainers and contribute to a project that benefits the R community worldwide.

