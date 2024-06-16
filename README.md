# PEN200-OSCP-DynamicCheatSheat

A dynamic cheat sheet for PEN-200 and OSCP made with Google Sheets.

## Get It

Access to the [Google Sheet](https://docs.google.com/spreadsheets/d/13g6RFbaS-5KJcETONOSSV7vNSh9OXCgbNak8WM2H1A0/edit?gid=1858408689#gid=1858408689).

Then, "File" > "Make a copy" to make it your own.

## Basic Usage

1. Navigate to "DCS" sheet (the rightmost one).
2. Change "Target Host" drop down. You'll see IP address in commands change.

    ![image](https://github.com/laysakura/PEN200-OSCP-DynamicCheatSheat/assets/498788/59e3c7d4-a715-4985-87c0-0e813ce20e4b)

3. Change "Target User" drop down. You'll see usernames and passwords in cmmands change.

    ![image](https://github.com/laysakura/PEN200-OSCP-DynamicCheatSheat/assets/498788/2ae5c48a-11d4-421c-aabf-01da13e5b196)

4. "Purpose" and "Target Service (port)" drop down menus filters command rows.

    ![image](https://github.com/laysakura/PEN200-OSCP-DynamicCheatSheat/assets/498788/45ec1691-ee36-4256-82b6-96cc4c3c084e)
   

## Settings: Change "host" and "user" sheet to your victims

You need to set "host":

<img width="745" alt="image" src="https://github.com/laysakura/PEN200-OSCP-DynamicCheatSheat/assets/498788/f4716cb4-2931-499c-9128-8a9b1f77b5ae">

---

And "user":

<img width="1110" alt="image" src="https://github.com/laysakura/PEN200-OSCP-DynamicCheatSheat/assets/498788/134ec295-4870-4d85-a157-2a7e9b1baf4f">

---

According to your targets.

## Basic Customization

You may customize "Purpose" and "Target Service (port)" in "purpose&service" sheet.

<img width="449" alt="image" src="https://github.com/laysakura/PEN200-OSCP-DynamicCheatSheat/assets/498788/eff986f2-6e70-494a-b2f1-d5bf1ed32f7f">

---

Also, you may add/edit your commands in "template" sheet.

<img width="1173" alt="image" src="https://github.com/laysakura/PEN200-OSCP-DynamicCheatSheat/assets/498788/8c535ced-02ea-4bd7-b864-1184330c34ef">

## How it Works

Take a look at A6 cell in "DCS" sheet.

<img width="683" alt="image" src="https://github.com/laysakura/PEN200-OSCP-DynamicCheatSheat/assets/498788/91ab2216-9c06-4266-b9cd-f91b7c6bc15a">

It brings commands from "template" sheet and substitutes variables (e.g. $RHOST, $DOMAIN, ...) defined in line 1 to 4.

## LICENSE

This work is licensed under the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

You are free to:

- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:

- Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
