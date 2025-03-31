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
## Making data.table Even Better

### About my project 
This project is all about making the data.table package for the R programming language even better. data.table is a super-fast and efficient way to work with data, and all I need is to fix some existing issues, add new features that people have asked for, improve the documentation, and make the way data is displayed cleaner. This will help everyone who uses data.table to work with their data more easily and effectively.

### Goal for the project
My main goal is to tackle some of the things that users have pointed out as needing improvement in data.table. Since I've been actively contributing to the project for a while now, I have a good handle on how it works. Specifically, I understand:

- The basics of how data.table helps you work with data quickly.
- Important tools within data.table like fread() (for reading files), setDT() (for making data tables), and how data tables are joined together.
- The underlying code (written in a language called C) that makes data.table so fast and efficient.
- Common problems and areas where things could be faster, based on my previous work on the project.

Here's a breakdown of the specific areas I'll be focusing on:

| **Focus**                | **Issues**                                            | **Description**                                                                                                                |
|--------------------------|-------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| **Top User Request**     | [#1636]                                              | Add a feature in fread to support thousand operator                                             |
| **Beginner's Tasks**     | [#6219], [#6641], [#4259], [#6702], [#5829], [#5609], [#5034] | Smaller tasks that help build familiarity with the codebase and resolve common issues new contributors can start with.        |
| **Making Things Better** | [#6036], [#5034], [#5913]                            | Enhancements aimed at improving existing functionalities of data.table.                                                       |
| **New Features**         | [#6341], [#5415]                                     | Requests for additional capabilities that users want, expanding data.table’s toolset.                                         |
| **Improving Documentation** | [#2487], [#2002], [#6638], [#6691], [#5321], [#6323], [#6720] | Updates and clarifications to help guides and vignettes, ensuring they’re easier to understand and more comprehensive.        |
| **Cleaner Output**       | [#904]                                               | Refining how data.table displays data on the screen, making it more readable and user-friendly.                               |

### My plans to get it done
Here's my plan for tackling these goals:

#### 1. Understanding the Problems:
- First thing to do is reproduce the issue if its a bug or something and carefully read through each of the chosen issues to fully understand the problem .
- Look at the specific parts of the data.table code (both the main R code and the faster C code) that are related to each issue.
- Also check past discussions and changes to the code to understand the history.

#### 2. Figuring Out Solutions:
- For the more complicated issues, come up with a few different ways to solve them and discuss these approaches with the mentors.
- Think about how each solution might affect the speed, how easy it will be to maintain the code, whether it will still work with older versions of data.table, and if it fits with how data.table is generally designed.
- Write a short report comparing the good and bad points of each solution to help the mentors and me decide on the best approach.
  
#### 3. Making the Changes:
- Start by working on the most important issue first.
- Write the code to fix the issues and add the new features, making sure it follows the existing style of the data.table code and ensure my changs doesn't break anything.
- Share my code changes regularly on GitHub so the mentors can give me feedback and I can make improvements.

#### 4. Improving the Help Guides:
- Update the documentation files (called vignettes and man pages) to explain any changes I've made and any new features I've added.
- Make sure to include clear explanations and examples, especially for the more complex parts, so it's easier for everyone to learn and use data.table.

### How will I make sure everything works?
Use a careful testing process:

#### 1. Testing Each Part:
- Write specific tests to check if the new code and the changes I've made are working correctly and after discussing with mentor or community will place them in test.Rraw if needed.
- Also test unusual situations and edge cases to make sure the code is strong and doesn't break under different conditions.

#### 2. Checking Speed and Memory:
- Learn to use tools like valgrind and Rprof to look for any problems with how the code uses memory or if there are any areas that could be slower than they should be.
- Run tests to measure the speed of the code before and after my changes to make sure the optimizations are actually making things faster.

#### 3. Preventing Problems:
- Compare the results of my changed code with how older versions of data.table worked to make sure I haven't introduced any new bugs.
- Run all the tests on large amounts of data to simulate real-world use and make sure everything is stable.

To outline my approach to resolving issues, I have developed a well-structured plan that addresses each category, including the top user requests, enhancements, feature requests, and documentation improvements.

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

## My Plan for the Summer:
Here's a rough idea of how to spend time over the 12 weeks (this might change a bit based on feedback and how complex the issues turn out to be):
Keep track of progress each week and let the mentors know if there are any challenges. Also make sure to prioritize tasks based on importance and how they fit together.

### Potential Challenges and How to Overcome Them:
Here are some things that might be tricky and plans for handling them:

#### 1. Understanding the Existing Code:
- Spend plenty of time studying the important parts of the data.table code, especially the code that’s used most often and needs to be really fast.  
- Use special debugging tools and ask mentors for help if stuck on any complicated parts.

#### 2. Making Sure Things Still Work:
- Be very careful to make changes in a way that doesn’t break any existing features of data.table.  
- Run lots of tests in different situations to catch any problems early on.

#### 3. Staying on Schedule:
- Stick to the planned timeline and break down bigger tasks into smaller, more manageable steps.  
- Focus on the most important tasks first and let mentors know if falling behind.

### How to Communicate:
- Keep in touch with the mentors regularly using their preferred methods (like GitHub, email, etc.).  
- Send weekly updates on progress, ask for feedback on ideas and code, and respond quickly to questions or concerns. Commit to being a good communicator and collaborator throughout the summer.

## Timeline 

Here, I have provided an estimated end date for each task along with their expected duration. There is a long period of time until the coding period starts (proposal selection period + community bonding period), which I plan to use for getting familiar with the data.table package, its internal structure, efficient handling of data, key functions such as fread() and setDT(), and understanding the underlying C code that drives its performance and on regular basis doing the same job as I’m going to do at the start of official period.

This plan outlines how I'll spend my summer improving data.table. It's designed to be organized and efficient, ensuring I deliver valuable contributions.

### Phase 1: Before Coding Starts
#### Getting Ready:
- Become very familiar with the data.table code.
- The issues to be worked on will be studied carefully.
- Set up my coding environment and ensure Git is working well.

#### Early Contributions:
- Start working on small tasks or discussions related to the issues.
- Begin talking with my mentors about my plans.
- The data.table way of contributing code will be learned.

### Phase 2: Coding (June - August)

#### Week 1: 1st June to 7th June:
- Regarding #1636, add a thousands argument in R/fread.R, validate it, and pass to C. Extend key structs in C to store this parameter.
- Create a reusable buffer for each thread to strip thousand separators.
- Integrate this buffer into numeric detection and parsing routines (coerce.c, read.c)
- Begin basic tests for simple CSV inputs, including malformed data. And present it to the mentors by the weekend for review

#### Week 2: 8th June to 14th June:
- Implement mentors’ suggestions, if any in the code.
- Expand test coverage: negative values, inconsistent separators, mixed columns.  
- Check multi-threaded scenarios for concurrency safety.
- Perform benchmark tests to compare performance in terms of speed and memory optimize buffer management and resolve any performance issues.
- Conclude with large-scale tests, final reviews of maintainers.

### Weeks 3-4: Beginner-Friendly Issues & Documentation  
**Focus:** [#6641], [#4259], [#6219] (Beginner-friendly), [#6691], [#6638] (Documentation)

- **Implementation Steps:**  
  - Review code segments where these beginner-friendly issues reside, assess their scope, and propose fixes or optimizations.  
  - Coordinate with mentors to confirm any design changes (e.g., simplifying code paths, aligning function arguments with established naming conventions).  
  - Begin updating documentation for [#6691] and [#6638], clarifying usage examples and adding relevant test cases.

- **Testing & Review:**  
  - Run newly added tests locally for each issue to confirm correct behavior.  
  - Ensure no performance regressions by benchmarking against pre-fix conditions.  
  - Seek mentor feedback on documentation clarity and consistency.

### Weeks 5-6: Enhancements & Documentation  
**Focus:** [#6036], [#5034] (Enhancements), [#5321] (Documentation)

- **Implementation Steps:**  
  - Address enhancement [#6036] by analyzing user-reported performance concerns or feature gaps; optimize the relevant R/C code paths.  
  - Resolve printing or formatting improvements for [#5034], ensuring consistency with data.table output style.  
  - Update documentation for [#5321], adding examples and clarifying parameter usage.

- **Testing & Review:**  
  - Validate enhancements with unit tests that measure both correctness and speed.  
  - Conduct real-world scenario tests to ensure changes integrate smoothly.  
  - Incorporate mentor and community feedback to finalize documentation improvements.

### Weeks 7-8: Feature Requests & Documentation  
**Focus:** [#6341], [#5415] (New Features), [#6323] (Documentation)

- **Implementation Steps:**  
  - Implement requested features in a modular way, adding arguments or functions in both R and the underlying C code as necessary.  
  - Verify backward compatibility, so existing workflows remain unaffected.  
  - Update or create vignettes/man pages for [#6323], showing how to use new features effectively.

- **Testing & Review:**  
  - Write tests that cover feature functionality (including edge cases and erroneous inputs).  
  - Run performance checks (e.g., microbenchmark) to ensure new features do not degrade speed.  
  - Discuss any design concerns or special cases with mentors before merging.

### Weeks 9-10: Additional Beginner Issues & Print Functionality  
**Focus:** [#6702], [#5829] (Beginner-friendly), [#904] (Print)

- **Implementation Steps:**  
  - Investigate and fix selected beginner-friendly issues, focusing on code clarity and user-facing messages.  
  - Enhance print functionality [#904], ensuring large data.table outputs are more readable (e.g., truncated columns, wrapped text).  
  - Keep interactive feedback loops with mentors to align solutions with data.table standards.

- **Testing & Review:**  
  - Add tests for each resolved issue, including corner cases (e.g., empty data.tables).  
  - Confirm printing modifications improve usability without affecting performance.  
  - Incorporate mentor feedback and refine as needed for final acceptance.

### Week 11: Remaining Beginner Issues & Documentation  
**Focus:** [#5609], [#5039] (Beginner-friendly), [#2487], [#2002] (Documentation)

- **Implementation Steps:**  
  - Address the last batch of beginner-friendly issues, ensuring consistent function behavior across different inputs.  
  - Finalize documentation clarifications and updates, including adding more examples for advanced functions where necessary.  
  - Coordinate with mentors to confirm any final design decisions or doc layout changes.

- **Testing & Review:**  
  - Merge newly added tests with the existing suite, ensuring no overlapping regressions appear.  
  - Perform a broader review of all documentation changes to maintain consistent style and clarity.  
  - Incorporate final community feedback before the last phase.

### Week 12: Final Integration & Reporting  
- **Final Testing & Cleanup:**  
  - Conduct comprehensive testing for all completed issues and ensure code follows data.table conventions.  
  - Review memory and performance benchmarks across test libraries and large sample datasets.

- **Documentation Review & Reporting:**  
  - Verify all man pages, vignettes, and example code demonstrate new or changed functionality clearly.  
  - Prepare and submit the final GSoC project report, summarizing each fix, enhancement, and documentation update.  
  - Coordinate with mentors to address any last-minute concerns.

This schedule mirrors the detailed approach used for Weeks 1 and 2, ensuring that each set of issues is addressed with clear goals, implementation plans, and testing strategies. It also allows for iterative feedback and refinement from mentors and the broader data.table community.

## Management of Coding Project

I plan to commit my code changes frequently, ideally every day or even multiple times a day when I'm actively working on something. Each commit will be a small, logical step in the development process, focusing on one specific improvement or fix. This makes it easier to track progress and for others to understand the changes. Each commit will also have a clear and short message describing what was done.

Before committing any code change, I'll make sure it's thoroughly tested. The data.table project requires that every new feature or bug fix has its own tests. These tests will be added to the inst/tests/tests.Rraw file. I'll also double-check that these new tests actually fail on the original code before my changes, just to be sure they are testing the right thing. The comments in the test code will include the issue number it relates to.

My approach to testing will involve writing tests for individual parts of the code (unit tests) and also tests to make sure everything works together correctly. I'll also pay attention to how fast the code runs and how much memory it uses. I'll compare the performance of my changes to older versions of data.table to make sure I'm not making things slower.

I'll keep the mentors updated about all the key improvements by mailing them twice a week. It is important to take their feedback before attempting any objectives so that the work proceeds smoothly without any hindrance. All my methods will be transparent and will be strictly according to the timeline.

### Possible change in commit behavior that would indicate a problem

If I suddenly stop committing code for a some time, it might mean I'm facing a problem I can't solve on my own and need help. Similarly, if I make very large commits with many unrelated changes, it could indicate that I'm not breaking down the work into manageable steps. If the commit messages become vague or don't explain what's being changed, that could also be a sign that things aren't going as smoothly as they should. Consistent, small commits with clear messages will show that I'm making steady progress and that the project is on track.
So keeping in touch with mentor and community will be one of its best solution that I know as of now.

## Project Impact on data.table Usability and Performance
This Google Summer of Code project aims to significantly enhance data.table by addressing key user needs and optimizing core functionalities. This project will focus on making data.table more performant and user-friendly.
The proposed improvements will directly impact the data.table community by:
- Increasing Operational Efficiency: This project will optimize data.table operations (e.g., fread, joins, sorting), resulting in faster execution and reduced resource usage. This will be particularly beneficial for users handling large datasets.
- Improving User Accessibility: By addressing specific feature requests and clarifying documentation, this project will make data.table more intuitive and accessible to a wider audience, including those new to the package.
- Facilitating Best Practices: improved documentation and clearer error messages will help users understand and implement best practices for data.table usage.
- Strengthening Community Contribution: By making the package more user-friendly and well-documented, this project will encourage more users to contribute to the data.table ecosystem.
- Building a More Robust Tool: Resolving identified bugs and implementing requested features will contribute to a more stable and reliable data.table package.

The desired outcome is to position data.table as an even more powerful and efficient tool within the R ecosystem, building upon its already strong foundation. The project's success will be measured by improved performance, reduced user friction, and increased community engagement.

### TEST
### For test qualification , there we have to merege 1 pr , so below are my Contributions So Far

I've already made several contributions to data.table, with four pull requests successfully merged. I'm also actively working on other improvements, one is ready to review an dworking on others. Here's a quick overview of each merged pull request:

#### PR #6816: Fixes Index Printing

**What it fixed:** This pull request solved a problem where `print.data.table()` would fail when you tried to show indices (using `options(datatable.show.indices = TRUE)`). This happened because the code expected a certain number of columns, but the actual data had a different number. The error message was:

```
Error in rbind(abbs, toprint) : number of columns of result is not a multiple of vector length (arg 1)
```

**Impact:** The fix makes the `print.data.table()` function more reliable when showing indices, ensuring the index information is displayed correctly without causing errors.

**Challenges:** As someone new to data.table and R, I initially struggled with understanding the internal structure.

**How I overcame them:** I got a lot of help from the data.table community. Their guidance helped me understand the problem and find a working solution.

**Test Case:**

```r
DT <- data.table(a = 1:2, b = 2:1)
setindex(DT, b)
# make sure that print(DT) doesn't warn due to the header missing index column types, #6806
# can't use output= here because the print() call is outside withCallingHandlers(...)
test(2307, { capture.output(print(DT, class = TRUE, show.indices = TRUE)); TRUE })
```

#### PR #6865: Consistent Key Handling

**What it fixed:** The `key()` function wasn't behaving consistently when converting objects to data.table. Specifically, setting a key during conversion (`key(as.data.table(x, key = <key>))`) didn't always work as expected for tibbles or unkeyed data.tables. Also, `key(as.data.table(x))` would sometimes keep the original key when it should have returned `NULL`.

**What was fixed:** Now, `as.data.table()` behaves consistently:

*   **Explicit Key Setting:** If you specify a key, it's always set, regardless of the input type.
*   **Key Preservation:** If you don't specify a key, the existing key (if any) is preserved.
*   **Key Removal:** If you set `key = NULL`, any existing key is removed.

**Impact:** These changes make key handling more predictable and easier to use.

#### PR #6870: Clearer Argument Names

**What it fixed:** This pull request replaced abbreviated argument names (like `id`, `fun.agg`, `measure`) with their full names (`id.vars`, `fun.aggregate`, `measure.vars`) in the reshape vignettes.

**Impact:** This improves the clarity and consistency of the documentation, making it easier to understand the examples.

**Learning:** I learned the importance of using clear and consistent argument names, gained experience updating documentation in multiple languages, and improved my attention to detail.

#### PR #5455: Explicitly Specify `on = .NATURAL`

**What it fixed:** This pull request updated the error message for natural joins to include the phrase "with the keyword 'on = .NATURAL'".

**Impact:** This makes the error message more helpful by clearly telling users how to perform a natural join.

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

