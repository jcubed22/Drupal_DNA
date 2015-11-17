# _DNA Encoder_

##### _Returns matching nucleotide sequence for user input, 11/17/15_

#### By _**Jordan J. Johansen**_

## Description

_The home page is a basic page that has been created to display the links found on the left sidebar under "AJAX Links" using, surprise surprise, AJAX.  Clicking on the "DNA Encoder" link under "Navigation" takes the user to a page where they are able to enter in a nucleotide sequence (i.e. the letters "G", "T", "C", or "A".  Once submitted, the form will redirect to a second page which will return the user inputted sequence, and the nucleotide pairs to match._

## Setup
* _Clone the repository from GitHub._

* On Mac:
Set the MAMP root directory to the project folder.  Navigate to MAMP's phpMyAdmin page and import the database zip file found in sites/db\_backup. (dna\_database.sql.zip)

* _After selecting the newly imported database, click on the "Privileges" tab and add create a user with these settings:<br>
User Name: dna_admin  <br>
host: localhost<br>
Password: epicodus_

* _On Windows:
Do the same as above, but through WAMP, or whatever server you're using._

* _Open your browser and go to localhost:8888._

* _Database Information:_<br>
Database name: dna\_database<br>
_Database user: admin_<br>
_Password: epicodus_

* _Site admin account information_<br>
_Admin user: admin_<br>
_Password: admin_

## Technologies Used
_Drupal 7.41, SimpleTest, AJAX._

## Legal

Copyright (c) 2015 Jordan J. Johansen

This software is licensed under the MIT license.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
