# :house_with_garden: KSH hostel :house_with_garden:	

This is a website built with Javascript, Bootstrap and SASS. Users can search all Kaohsiung hostel informations, register and change profile picture and password. 

Demo here :point_down: <p></p>
<a href="https://ksh-project-vercel-1.vercel.app//"><img src="https://img.shields.io/badge/link-KSH.hostel-1?style=flat&logoColor=red&labelColor=%237B7B7B&color=%23FFDA6A" alt="portfolio"></a>

## Project View
Desktop (1366px)

![image](https://i.ibb.co/1Xyx46B/1-header-before-Login.png)

You can click on this link to view more pictures :point_right::point_right::point_right: 
<a href="https://drive.google.com/drive/folders/16bUqu92zvwPCL3W7V19hLtldLZySoecc?usp=drive_link">KSH hostel</a>

## Features
|          Components               | Description                                                  | URL                  |
| :--------------------------: | ------------------------------------------------------------ | -------------------- |
|    Home    | 1. Users can either key in hostel name or select region to search <br>2. If the search result is failed, the users will be reminded <br>3. Links to registration or login are provided in the navigation bar  | /home.html      |
|      Login       | 1. There is a toggle between login form and register form  <br>2. If the input is invalid, the form submission is prevented and users will be reminded <br>3. Users will be directed to Home page after successful login or login form after registration <br>4. The navigation logo is replaced with users' profile picture if it exists | /login.html         |
|      Account        | Section A: Change profile picture<br> 1. Users can change a picture in JPG, JPEG, PNG or ICO format <br> 2. A preview is displayed if the picture format is valid<br> 3. A cancel button and a upload button are provided for users to remove the preview or submmit the picture to the backend.   <br><br> Section B: Change password<br> 1. If the input format is invalid, the form submission is prevented<br> 2. Users will receive feedback from the backend after submission  | /account.html         |



## Tools
1. Designs&nbsp; (&nbsp;Bootstrap + SASS&nbsp;)
2. Building tool&nbsp; (&nbsp;Webpack&nbsp;)
3. Storage&nbsp; (&nbsp;localStorage&nbsp;)
4. Validation&nbsp; (&nbsp;Bootstrap validator + jQuery validate&nbsp;)
5. HTTP request&nbsp; (&nbsp;Axios&nbsp;)
6. Backend&nbsp; (&nbsp;External APIs&nbsp;)
7. Deployment&nbsp; (&nbsp;Vercel&nbsp;)

## Bugs/Future plans
1. After users logged in, the navigation logo should be replaced with users' profile picture. The replacement takes 1-2 seconds when the page is refreshed. The desired effect should be: the picture is directly rendered when the page is refreshed.    

## Installation
Please follow the instructions to get a copy of this project.

### Prerequisites
 * <a href="https://docs.npmjs.com/downloading-and-installing-node-js-and-npm">npm</a> 

### Clone
```sh
git clone https://github.com/wooiseong/portfolio-project-vercel.git
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Contact
* <a href= "mailto:wooiseongseong96@gmail.com">Email:  &nbsp;wooiseongseong96@gmail.com</a>
