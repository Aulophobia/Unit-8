# Unit-8

Laurence Bramblett
# Project 7 - WordPress Pentesting

Time spent: **X** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

### 1. (Required) Vulnerability Name or ID
  - [ ] Summary: Enumerating Users
    - Vulnerability types: Web Application vulnerability
    - Tested in version:4.2
    - Fixed in version: 4.6
  - [ ] GIF Walkthrough: ![Enumerating Users](https://user-images.githubusercontent.com/89473315/138620168-5e87b709-1d50-4c8c-bc0a-91e45cf445ce.gif)

  - [ ] Steps to recreate: Use command wpscan --url http://192.168.33.10/ -e u vt
  - [ ] Affected source code:



### 2. (Required) Vulnerability Name or ID User Enumerating “2” CVE 2009-2335
  - [ ] Summary: You will receive a “confirmation” if you have chosen a correct username.
    - Vulnerability types: Information Exposure
    - Tested in version:4.2
    - Fixed in version: unknown
  - [ ] GIF Walkthrough: ![Enumerating Users 2](https://user-images.githubusercontent.com/89473315/138620178-a19d08ec-e08f-4e42-98ad-4015c5fcad8e.gif)

  - [ ] Steps to recreate: Enter a username with any password and the ERROR message will tell you if it is a valid username.
  - [ ] Affected source code:
  

### 3. (Required) Vulnerability Name or ID Information Overexposure
  - [ ] Summary: You can navigate to /wp-admin/css or /wp-admin/js to view the directory listing
    - Vulnerability types: Information Overexposure
    - Tested in version: 4.2
    - Fixed in version: unknown
  - [ ] GIF Walkthrough: ![Information Overexposure](https://user-images.githubusercontent.com/89473315/138620183-33a1e147-d070-44af-a8ab-afdc28ef97b2.gif)

  - [ ] Steps to recreate: navigate to /wp-admin/css or /wp-admin/js to view directories.
  - [ ] Affected source code:

 

## Assets

List any additional assets, such as scripts or files
WPScan
## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with ScreenToGif.

## Notes

Describe any challenges encountered while doing the work
