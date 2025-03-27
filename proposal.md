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
- Mentors
- Coding Plan And Methods
- Timeline
- Code

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

I have also contributed to refactoring legacy code, improving maintainability, and updating documentation. In addition, I have written unit tests to cover edge cases and ensure system stability. This work has improved the robustness of the codebase and provided me with valuable insights into writing clean, efficient, and maintainable code.

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

## Mentors
- Evaluating mentor name and email: TOBY DYLAN HOCKING, toby.hocking@r-project.org
- Co-mentor name(s) and email(s): JOSHUA WU, joshuawu2004@gmail.com

**Have you been in touch with the mentors? When and how?**

Yes, I have been in touch with my mentor, Joshua Wu, even before I began contributing. I reached out to him via email, seeking his guidance. His valuable advice greatly helped me get started with this package.

## MY MOTIVATION

I am confident that I would be a valuable contributor to this project, driven by a strong passion for learning, hands-on experience, and an insatiable curiosity for exploring complex systems. Since February 2025, I've been contributing to data.table, where each pull request feels less like work and more like solving a fun puzzle—occasionally with a surprise twist! Fixing issues and improving documentation has sharpened my understanding of its internals, from blazing-fast data handling to clever C-level optimizations.

What excites me most about data.table is how it processes massive datasets with amazing speed. As someone interested in data science and machine learning, I know how important fast data handling is for providing quality training data to build better models. Improving data.table isn't just about fixing bugs for me—it's about helping the data science community by making data processing more efficient, which leads to smarter insights and better models.

Being part of the data.table community has been a great experience. The people here are always ready to help, and every interaction has taught me something new, from understanding C code to learning about R's internals. This supportive environment motivates me to keep contributing and learning more.

I'm also excited about the challenge of working on a large and complex codebase like data.table. Understanding and contributing to such a widely used open-source project pushes me to improve my technical skills while being part of a community that values performance and efficiency. I'm eager to keep refining data.table and make it even better for the broader data science and analytics community.

## SCHEDULED CONFLICTS

I am fully prepared to dedicate myself to the R GSoC project over the summer, treating it as a full-time responsibility. I have no internships, academic obligations, or personal commitments that could interfere with my ability to focus on the project. This allows me to allocate my complete attention and effort toward achieving the project's objectives.

With no external distractions, I am confident in my ability to contribute meaningfully, collaborate effectively with mentors and the community, and ensure steady progress. I am committed to maintaining a high standard of work and delivering quality results within the expected timelines.

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
- Top User Request: I'll spend about two weeks working on the most important issue that community have asked to be fixed, among which top request issue I'm going to solve will be [#1636].
- Beginner's task: [#6219, #6641, #4259, #6702, #5829, #5609, 5034]
- Making Things Better: I'll address issues labeled enhancement [#6036, #5034, #5913] that aim to improve how data.table already works.
- New Features: I'll work on adding some new tools and capabilities that users have requested, labeled [#6341, #5415].
- Improving Documentation: I'll make the help guides and explanations for data.table clearer and easier to understand, based on issues [#2487, #2002, #6638, #6691, #5321, #6323, #6720].
- Cleaner Output: I'll refine how data.table shows you your data on the screen, based on issue [#904].

### My plans to get it done
Here's my plan for tackling these goals:

#### 1. Understanding the Problems:
- First thing I'm going to do is to reproduce the issue if it is a bug or something on my machine.
- I'll carefully read through each of the chosen issues on GitHub to fully understand what the problem is, what users expect, and if anyone has already discussed potential solutions.
- I'll group the issues based on how complex they are and how much impact they have.
- I'll look at the specific parts of the data.table code (both the main R code and the faster C code) that are related to each issue.
- I'll also check past discussions and changes to the code to understand the history.

#### 2. Figuring Out Solutions:
- For the more complicated issues, I'll come up with a few different ways to solve them and discuss these approaches with the mentors.
- I'll think about how each solution might affect the speed, how easy it will be to maintain the code, whether it will still work with older versions of data.table, and if it fits with how data.table is generally designed.
- I'll learn to use a tool called microbenchmark to test how fast different solutions are on real-world data.
- I'll write a short report comparing the good and bad points of each solution to help the mentors and me decide on the best approach.
  
#### 3. Making the Changes:
- I'll start by working on the most important issue first.
- I'll write the code to fix the issues and add the new features, making sure it follows the existing style of the data.table code.
- I'll double-check that my changes don't break anything.
- I'll share my code changes regularly on GitHub so the mentors can give me feedback and I can make improvements.

#### 4. Improving the Help Guides:
- I'll update the documentation files (called vignettes and man pages) to explain any changes I've made and any new features I've added.
- I'll make sure to include clear explanations and examples, especially for the more complex parts, so it's easier for everyone to learn and use data.table.

### How will I make sure everything works?
I'll use a careful testing process:

#### 1. Testing Each Part:
- I'll write specific tests to check if the new code and the changes I've made are working correctly and after discussing with mentor or community will place them in test.Rraw if needed.
- I'll also test unusual situations and edge cases to make sure the code is strong and doesn't break under different conditions.

#### 2. Checking Speed and Memory:
- I'll learn to use tools like valgrind and Rprof to look for any problems with how the code uses memory or if there are any areas that could be slower than they should be.
- I'll run tests to measure the speed of the code before and after my changes to make sure the optimizations are actually making things faster.

#### 3. Preventing Problems:
- I'll compare the results of my changed code with how older versions of data.table worked to make sure I haven't introduced any new bugs.
- I'll run all the tests on large amounts of data to simulate real-world use and make sure everything is stable.

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
  char thousands_sep;      // Thousands separator
  // ... other global fields
} FreadGlobalArgs;

typedef struct {
  char *buffer;            // Reusable buffer for stripping separators
  size_t buffer_size;      // Current capacity of the buffer
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
dt <- fread("huge_file.gz")  # Warning: "File is truncated"
sum(dt$value)  # Returns incorrect result with no obvious error
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
Here's a rough idea of how I'll spend my time over the 12 weeks (this might change a bit based on feedback and how complex the issues turn out to be):
I'll keep track of my progress each week and let the mentors know if I'm facing any challenges. I'll also make sure to prioritize tasks based on how important they are and how they fit together.

### Potential Challenges and How I'll Overcome Them:
Here are some things that might be tricky and how I plan to deal with them:

#### 1. Understanding the Existing Code:
- I'll spend plenty of time studying the important parts of the data.table code, especially the code that's used most often and needs to be really fast.
- I'll use special debugging tools and ask the mentors for help if I get stuck on any complicated parts.

#### 2. Making Sure Things Still Work:
- I'll be very careful to make changes in a way that doesn't break any existing features of data.table.
- I'll run lots of tests in different situations to catch any problems early on.

#### 3. Staying on Schedule:
- I'll stick to my planned timeline and break down bigger tasks into smaller, more manageable steps.
- I'll focus on the most important tasks first and let the mentors know if I think I might fall behind.

### How I'll Communicate:
- I'll keep in touch with the mentors regularly using the methods they prefer (like GitHub, email, etc.).
- I'll send weekly updates on my progress, ask for feedback on my ideas and code, and will respond quickly to any questions or concerns they have. I'm committed to being a good communicator and collaborator throughout the summer.

### What I Hope to Achieve:
By the end of this summer, I want to make data.table an even better tool for everyone. By fixing important issues, making it faster, and improving the documentation, I hope to contribute to the continued success and popularity of data.table in the R community.

## Timeline 

Here, I have provided an estimated end date for each task along with their expected duration. There is a long period of time until the coding period starts (proposal selection period + community bonding period), which I plan to use for getting familiar with the data.table package, its internal structure, efficient handling of data, key functions such as fread() and setDT(), and understanding the underlying C code that drives its performance and on regular basis doing the same job as I’m going to do at the start of official period.

This plan outlines how I'll spend my summer improving data.table. It's designed to be organized and efficient, ensuring I deliver valuable contributions.

### Phase 1: Getting Ready (Post Acceptance - Start of Coding)
- Setting up my workspace: I'll make sure I have R, RStudio, and Git installed and working smoothly. This is like setting up my tools before starting a big project.
- Learning the data.table way: I'll get familiar with how data.table developers work, including how to share code and contribute.
- Talking to my mentors: I'll establish clear ways to communicate with my mentors, so I can easily ask questions and get help.
- Understanding the issues: I'll carefully study the GitHub issues I'll be working on (like [#6036, #5034, etc.]). This means reading discussions and exploring the related parts of the data.table code.
- Exploring the data.table code: I'll get a good grasp of how data.table is organized, so my contributions fit in well.
- Initial mentor discussions: I will discuss my initial research with mentors and get feedback on my planned approach.

### Phase 2: Coding (June - August)

Google Summer of Code: data.table Project Timeline
This timeline details my plan for contributing to data.table during GSoC. The project will address a range of issues, from user requests to documentation improvements, ensuring a valuable contribution.

### Phase 1: Before Coding Starts
#### Getting Ready:
- I'll become very familiar with the data.table code.
- The issues I'll be working on will be studied carefully.
- I'll set up my coding environment and ensure Git is working well.

#### Early Contributions:
- I'll start working on small tasks or discussions related to the issues.
- I'll begin talking with my mentors about my plans.
- The data.table way of contributing code will be learned.

### Phase
#### Week 1: 1st June to 7th June:
- Add a thousands argument in R/fread.R, validate it, and pass to C. Extend key structs in C to store this parameter.
- Create a reusable buffer for each thread to strip thousand separators.
- Integrate this buffer into numeric detection and parsing routines (coerce.c, read.c)
- Begin basic tests for simple CSV inputs, including malformed data. And present it to the mentors by the weekend for review

#### Week 2: 8th June to 14th June:
- Implement mentors’ suggestions, if any in the code.
- Expand test coverage: negative values, inconsistent separators, mixed columns.  
- Check multi-threaded scenarios for concurrency safety.
- Perform benchmark tests to compare performance in terms of speed and memory optimize buffer management and resolve any performance issues.
- Conclude with large-scale tests, final reviews of maintainers.

#### Weeks 3-4:
- I'll work on beginner-friendly issues [6641] and [4259], [6219].
- I'll address documentation issue [6691] and [6638]

### July: Enhancements, Feature Requests, and Documentation
#### Weeks 5-6:
- I'll work on enhancements [6036] and [5034].
- I'll address documentation issue [5321].

#### Weeks 7-8:
- I'll begin working on feature requests [6341] and [5415].
- I'll address documentation issue [6323].

### August: Beginner Issues, Print, Documentation, and Finishing Up
#### Weeks 9-10:
- I'll address beginner-friendly issues [6702] and [5829].
- I'll work on print functionality issue [904].

#### Week 11:
- I'll address the remaining beginner-friendly issues: [5609] and [5039].
- I'll complete documentation issues [2487] and [2002].

#### Week 12:
- I'll do final testing and ensure everything works correctly.
- All the documentation will be reviewed.
- I'll write my final report for Google Summer of Code.

### Phase 3: After Coding
#### Final Checks:
- I'll address any feedback from my mentors.
- All code will be checked to ensure it follows the data.table rules.

#### Staying Involved:
- I'll be available to answer questions and help out.

### Important Notes:
- I plan to work on this project for 40+ hours each week.
- I'll communicate with my mentors regularly.
- I'll prioritize the most important tasks.
- I will write weekly blog posts.
- Weekends will be used to catch up, if needed.

This timeline is a plan, and I'm prepared to adjust it as needed. My goal is to make valuable contributions to the data.table project.

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

## Questions for me:
This section is voluntary reading:

### Why choose this project?
As a student doing learning growing in machine learning era I believe that it is my job to present tools of advanced scientific computing and intelligence in the simplest format possible. The advances in Machine Learning/Deep Learning/Artificial Intelligence and other allied fields should be accessible to a wider array of people. Domain experts, academic scholars, teachers, mathematicians, statisticians, scientists and their like have more domain knowledge than computer programmers in their respective fields. They are therefore best suited to make approximations in different machine learning models and draw interesting inferences using exploratory data analysis. This is something that could never be achieved without a certain level of domain knowledge.
Expecting these people to learn the intricacies of programming is counter-intuitive, hence it’s in everyone’s best interest that they be able to carry out their tasks with ease and in the least possible time.
I would really love to be a part of a package that can enhance the data manipulation and fast reading of files enhance the productivity of analysed data.

### Do you consider yourself fit for the project?
Absolutely. I'm genuinely enthusiastic about contributing to the data.table package, and I believe my skills and dedication align perfectly with the project's goals. The prospect of enhancing a tool that significantly impacts the efficiency of countless R users is incredibly motivating.
My deep dive into the data.table codebase, coupled with my thorough research into the specific GitHub issues ([#6036, #5034, etc.]), has given me a solid understanding of the challenges and potential solutions. I'm committed to delivering well-tested, documented, and maintainable code that seamlessly integrates with the existing package.
Furthermore, my proactive approach to learning the data.table development workflow, setting up a robust development environment, and establishing clear communication channels with mentors will ensure a smooth and productive GSoC experience. I understand the importance of clear communication, and I'm ready to ask for feedback, and help, when needed.
While my experience with large open-source projects is still developing, my consistent work on personal and academic projects has solidified my Git and GitHub proficiency. I am comfortable with collaborative development, and I am ready to adhere to the data.table contribution guidelines.
I am confident that my passion for efficient code, my dedication to thorough research and testing, and my commitment to clear communication will allow me to make valuable contributions to the data.table project. I'm eager to learn from the experienced maintainers and contribute to a project that benefits the R community worldwide.

