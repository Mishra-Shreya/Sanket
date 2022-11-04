# Sanket
Introducing... **SANKET** - 
_**Speech to Indian Sign Language Translator**_

## Getting Started

**Sanket** is (currently) an _Android_ based _Indian Sign Langauge Mediator mobile app_ made using _Flutter_ and _Blender_. It is a virtual interpreter that translates Speech to Indian Sign Language (ISL) and helps to bridge the communication gap between people of the speaking community and the deaf & hard of hearing (DHH) community.

_This project's created as a part of school-pbl-activity._

... Project's still under development :wink: ...


## Table of contents

- [Installation](#installation)
- [Folder Structure](#folder-structure)
- [Screenshots](#screenshots)
- [Demo](#demo)
- [Conclusion](#conclusion)


## Installation

**Step 1:**

Download or clone this repo by using the link below:

```
https://github.com/Mishra-Shreya/Sanket.git
```

**Step 2:**

Go to project root and execute the following command in console to get the required dependencies: 

```
flutter pub get 
```

## Folder Structure
Here is the core folder structure.

```
flutter-app/
|- android
|- assets
|- ios
|- lib
|- test
```

Here is the folder structure we have been using in this project

```
lib/
|- main.dart
|- speechToSign.dart
|- utils.dart
```

Now, lets dive into the lib folder which has the main code for the application.

```
1- main.dart - This is the starting point of the application. 
2- speechToSign.dart — This file is the heart of the application. Major application level configurations : Home Screen UI, Translation logic are defined in this file.
3- utils.dart — This file contains all the utilities such as list for phrases, words, letters, etc for your translation.
```


## Screenshots 

<table>
<tr>
<td>Splash Screen</td>
<td>On Startup</td>
<td colspan="2">During Translation</td>
<td colspan="2">On Refresh</td>
</tr>
<tr>
<td><img src="https://user-images.githubusercontent.com/69296480/163388210-749c706e-93ff-4fc4-b79d-dfa58bfa52fb.jpg" width="125"></td>
<td><img src="https://user-images.githubusercontent.com/69296480/163388238-110fccb2-6e38-40d5-91b5-4454bda0c8dc.jpg" width="125"></td>
<td><img src="https://user-images.githubusercontent.com/69296480/163388245-0a2193f1-b39e-4b0d-b783-734590428406.jpg" width="125"></td>
<td><img src="https://user-images.githubusercontent.com/69296480/163388290-ec9aa348-cbc2-47a1-a09c-87f195d79be8.jpg" width="125"></td>
<td><img src="https://user-images.githubusercontent.com/69296480/163388312-a4ea2952-f601-4668-8714-91abf8b983f2.jpg" width="125"></td>
<td><img src="https://user-images.githubusercontent.com/69296480/163388328-4d870390-d89d-4f6a-be17-4a90b5db9aa8.jpg" width="125"></td>
</tr>
</table>

## Demo 

<img src="https://user-images.githubusercontent.com/69296480/192119484-c0ec4b9a-1a11-45d1-9ea5-eedb22d79618.gif" width="200">

## Conclusion

I will be happy to answer any questions that you may have, and if you want to lend a hand with the Sanket then please feel free to submit an issue and/or pull request 🙂

If you liked my work, don’t forget to ⭐ star the repo to show your support.

