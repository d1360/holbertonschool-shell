# IO Redirections and Filters

This repository contains a series of shell scripts to practice input-output redirections and filters in shell programming.

## Task Descriptions

1. **0. Hello World**  
   - **File**: `0-hello_world`
   - **Description**: Prints "Hello, World", followed by a new line to the standard output.
   - **Usage**:
     ```sh
     ./0-hello_world
     ```

2. **1. Confused smiley**  
   - **File**: `1-confused_smiley`
   - **Description**: Displays a confused smiley "(Ôo)".
   - **Usage**:
     ```sh
     ./1-confused_smiley
     ```

3. **2. Let's display a file**  
   - **File**: `2-hellofile`
   - **Description**: Displays the content of the `/etc/passwd` file.
   - **Usage**:
     ```sh
     ./2-hellofile
     ```

4. **3. What about 2?**  
   - **File**: `3-twofiles`
   - **Description**: Displays the content of `/etc/passwd` and `/etc/hosts`.
   - **Usage**:
     ```sh
     ./3-twofiles
     ```

5. **4. Last lines of a file**  
   - **File**: `4-lastlines`
   - **Description**: Displays the last 10 lines of `/etc/passwd`.
   - **Usage**:
     ```sh
     ./4-lastlines
     ```

6. **5. I'd prefer the first ones actually**  
   - **File**: `5-firstlines`
   - **Description**: Displays the first 10 lines of `/etc/passwd`.
   - **Usage**:
     ```sh
     ./5-firstlines
     ```

7. **6. Line #2**  
   - **File**: `6-third_line`
   - **Description**: Displays the third line of the file `iacta`.
   - **Usage**:
     ```sh
     ./6-third_line
     ```

8. **7. It is a good file that cuts iron without making a noise**  
   - **File**: `7-file`
   - **Description**: Creates a file named `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending with a new line.
   - **Usage**:
     ```sh
     ./7-file
     ```

9. **8. Save current state of directory**  
   - **File**: `8-cwd_state`
   - **Description**: Writes the result of `ls -la` into a file `ls_cwd_content`. If the file exists, it should be overwritten.
   - **Usage**:
     ```sh
     ./8-cwd_state
     ```

10. **9. Duplicate last line**  
    - **File**: `9-duplicate_last_line`
    - **Description**: Duplicates the last line of the file `iacta`.
    - **Usage**:
      ```sh
      ./9-duplicate_last_line
      ```

11. **10. No more javascript**  
    - **File**: `10-no_more_js`
    - **Description**: Deletes all regular files with a `.js` extension in the current directory and its subdirectories.
    - **Usage**:
      ```sh
      ./10-no_more_js
      ```

12. **11. Don't just count your directories, make your directories count**  
    - **File**: `11-directories`
    - **Description**: Counts the number of directories and subdirectories in the current directory. The current and parent directories are not counted.
    - **Usage**:
      ```sh
      ./11-directories
      ```

13. **12. What’s new**  
    - **File**: `12-newest_files`
    - **Description**: Displays the 10 newest files in the current directory, sorted from newest to oldest.
    - **Usage**:
      ```sh
      ./12-newest_files
      ```

14. **13. Being unique is better than being perfect**  
    - **File**: `13-unique`
    - **Description**: Takes a list of words as input and prints only words that appear exactly once. Words should be sorted.
    - **Usage**:
      ```sh
      cat list | ./13-unique
      ```

15. **14. It must be in that file**  
    - **File**: `14-findthatword`
    - **Description**: Displays lines containing the pattern "root" from the file `/etc/passwd`.
    - **Usage**:
      ```sh
      ./14-findthatword
      ```

16. **15. Count that word**  
    - **File**: `15-countthatword`
    - **Description**: Displays the number of lines that contain the pattern "bin" in the file `/etc/passwd`.
    - **Usage**:
      ```sh
      ./15-countthatword
      ```

17. **16. What's next?**  
    - **File**: `16-whatsnext`
    - **Description**: Displays lines containing the pattern "root" and 3 lines after them in the file `/etc/passwd`.
    - **Usage**:
      ```sh
      ./16-whatsnext
      ```

## Repository Structure

- **Directory**: `io_redirections_and_filters`
- **Scripts**: Each task is represented by a script file named according to the task number and description.
