# Loops, Conditions and parsing
This project is on Bash script and the usage of `env`, `cut`, loops, and conditional statements.


## Contributors
* **wingmann:** [wingmann9](https://github.com/wingmann9/)


## Tasks
* **0. Create a SSH RSA key pair**
  * [0-RSA_public_key.pub](./0-RSA_public_key.pub): A public SSH key created and uploaded to ALX intranet profile.


* **1. For Best School loop**
  * [1-for_best_school](./1-for_best_school): Bash script that displays `Best School` 10 times
  * Must use `for` loop (`while` and `until` are forbidden)


* **1. For Best School loop**
  * [1-for_best_school](./1-for_best_school): Bash script that displays `Best School` 10 times
  * Must use `for` loop (`while` and `until` are forbidden)


* **2. While Best School loop**
  * [2-while_best_school](./2-while_best_school): Bash script that displays `Best School` 10 times
  * Must use `while` loop (`for` and `until` are forbidden)


* **3. Until Best School loop**
  * [3-until_best_school](./3-until_best_school): Bash script that displays `Best School` 10 times
  * Must use `until` loop (`while` and `for` are forbidden)


* **4. If 9, say Hi!**
  * [4-if_9_say_hi](./4-if_9_say_hi): Bash script that displays `Best School` 10 times, but for the 9th iteration, displays `Best School` and then `Hi` on a new line
  * Must use `while` loop (`for` and `until` are forbidden)
  * Must use `if` statement


* **5. 4 bad luck, 8 is your chance**
  * [5-4_bad_luck_8_is_your_chance](./5-4_bad_luck_8_is_your_chance): Bash script that loops from 1 to 10 and:
    * displays `bad luck` for the 4th loop iteration
    * displays `good luck` for the 8th loop iteration
    * displays `Best School` for the other iterations
  * Must use `while` loop (`for` and `until` are forbidden)
  * Must use `if`, `elif` and `else` statements


* **6. Superstitious numbers**
  * [6-superstitious_numbers](./6-superstitious_numbers): Bash script that display numbers from 1 to 20 and:
    * displays `4` and then `bad luck from China` for the 4th loop iteration
    * displays `9` and then `bad luck from Japan` for the 9th loop iteration
    * displays `17` and then `bad luck from Italy` for the 17th loop iteration
  * Must use `while` loop (`for` and `until` are forbidden)
  * Must use `case` statement


* **7. Clock**
  * [7-clock](./7-clock): Bash script that display the time for 12 hours and 59 minutes:
    * displays hours from 0 to 12
    * displays minutes from 1 to 59
  * Must use `while` loop (`for` and `until` are forbidden)


* **8. For ls**
  * [8-for_ls](./8-for_ls): Bash script that displays:
    * The content of the current directory
    * In a list format
    * where only part of the name after the first dash is displayed
  * Must use `for` loop (`while` and `until` are forbidden)
  * Do not display hidden files


* **9. To file, or not to file**
  * [9-to_file_or_not_to_file](./9-to_file_or_not_to_file): Bash script that gives information about the `school` file
  * Must use `if` and `else` (`case` is forbidden)
  * Bash script should check if the file exists and print:
    * if the file exists: `school file exists`
    * if the file does not exist: `school file does not exist`
  * If the file exists, print:
    * if the file is empty: `school file is empty`
    * if the file is not empty: `school file is not empty`
    * if the file is a regular file: `school  is a regular file`
    * if the file is not a regular file: (nothing)


* **10. FizzBuzz**
  * [10-fizzbuzz](./10-fizzbuzz): Bash script that displays numbers from 1 to 100.
  * Displays `FizzBuzz` when the number is a multiple of 3 and 5
  * Displays `Fizz` when the number is a multiple of 3 
  * Displays `Buzz` when the number is a multiple of 5
  * In a list format


## Advanced Tasks
* **11. Read and cut**
  * [100-read_and_cut](./100-read_and_cut): Bash script that displays the content of the file `/etc/passwd` and only display:
    * username
    * user id
    * Home directory path for the user
  * Must use `while` loop (`for` and `until` are forbidden)


* **12. Tell the story of passwd**
  * [101-tell_the_story_of_passwd](./101-tell_the_story_of_passwd): Bash script that displays the content of the file `/etc/passwd`  using `while` loop + IFS
  * Must use `while` loop (`for` and `until` are forbidden)


* **13. Let's parse Apache logs**
  * [102-lets_parse_apache_logs](./102-lets_parse_apache_logs): Bash script that displays the visitor IP along with the `HTTP status code` from the Apache log file
  * Format: IP HTTP_CODE
    * in a list format
  * Must use `awk` (`for`,`while`, `until`, and `cut` are forbidden)


* **14. Dig the data**
  * [103-dig_the_data](./103-dig_the_data): Bash script that group visitors by IP and HTTP status code, and displays the data
  * Format:
    * OCCURENCE_NUMBER IP HTTP_CODE
    * In list format
  * Ordered in descending order for number of occurences
  * Must use `awk` (`for`,`while`, `until`, and `cut` are forbidden)

