# _Anagrams and Antigrams_
## _By: Antonio Cruz_
## Description

_This is an application that will determine whether two provided words are anagrams or antigrams._

## Setup


1. If you would like to view this project locally... :

2. Visit this link https://github.com/assassin56/ruby-friday_project7
 
3. Clone this repo by selecting the "clone or download" button. This will allow you to copy the repo's link.

4. While on the command line in your terminal, enter "git clone" followed by the copied url.

5. Enter "ls" to show a list of files and documents. One of them will be labeled "ruby-friday_project4. Use "cd" followed by the project directory name to navigate there.

6. While in project directory, open the contents of the directory, or use "code ." to enable the shortcut to open in Visual Studio Code.

7. When the project opens, drag the file named "index.html" to your preferred browser to view and use the webpage!

## Known Bugs
_No known bugs at this time_

## Technology

* _Git_
* _GitHub_
* _Gem_
* _Ruby_
* _Rspec_


## Specs

* Behavior: The program checks that the two word inputs both contain vowels
  * Input: "tea", "eat"
  * Ouput: true

* Behavior: The program will check if two words are anagrams.
  * Input: "tea", "eat"
  * Output: "These words are an anagram"

* Behavior: The program will check if two words are anitgrams.
  * Input: "sup", "hello"
  * Output: "This is an antigram"

* Behavior: The program will check if two inputs are actually words.
  * Input: 'spd', 'tnl'
  * Output: "Please input an actual word!"

* Behavior: The program will check that different cases do not effect the anagram check.
  * Input: 'Tea', 'Eat'
  * Output: "These words are an anagram"

* Behavior: The program will check multiple words that the user may have entered in both inputs for difference in length, and compare arrays accordingly.
  * Input: 'tea, stop, bread', 'eat', pots'
  * Output: ["tea", "", "stop", "", "bread"] (the longest array)

* Behavior: The program will eliminate spaces and punctuation should the user input more than one word per input, accounting for multiple anagram/antigrams.
  * Input: "tea, stop", "eat, pots"
  * Output: "These words are an anagram"
## Legal

#### MIT License

### Copyright (c) 2020 Antonio Cruz

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.