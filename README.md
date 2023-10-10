                                                                                                
# NextJs 13 Reels Watching app
### [Live Site: Saddam Reels](https://saddamreels.vercel.app/)

## Technologies

Saddam Reels is a full stack NextJS app with popular backend platform app-write.

* NextJS
* App-Write
* Tailwind CSS
* TypeScript
* Zustand
* React Advanced Cropper

## Description

It has following functionalities:

* User SignUp
* User Login
* Change Profile
* Upload videos/reels
* Adding comments to reels
* Dynamic search

## Demo Video with CMS

[](https://github.com/SHnice/saddam-reels/assets/108930470/b55fb2a5-4de7-4c6f-ab22-7778a5ef55b7)


## Demo Pictures

<kbd>![image](https://github.com/SHnice/saddam-reels/assets/108930470/f9aa7595-703f-4b74-8fd0-9d88d7db3361)</kbd>


<kbd>![image](https://github.com/SHnice/saddam-reels/assets/108930470/09d46c6a-c925-48ba-93ee-0feff6b05961)</kbd>


<kbd>![image](https://github.com/SHnice/saddam-reels/assets/108930470/ff1b7c95-fb2f-4059-8955-af66e032291f)</kbd>


<kbd>![image](https://github.com/SHnice/saddam-reels/assets/108930470/7d3e0b90-291e-41ad-becf-d9698335e69b)</kbd>


<kbd>![image](https://github.com/SHnice/saddam-reels/assets/108930470/51bc0e0e-40f5-486e-a4ef-688407cf1442)</kbd>


## AppWrite Schema

### Profile Collection:
| Key | Type |
| --- | --- |
| `Document ID` | String |
| `image` | String |
| `bio` | String |
| `user_id` | String |
| `name` | String |


### Post Collection:
| Key | Type |
| --- | --- |
| `Document ID` | String |
| `user_id` | String |
| `video_url` | String |
| `text` | String |
| `created_at` | String |
    

### Like Collection:
| Key | Type |
| --- | --- |
| `Document ID` | String |
| `user_id` | String |
| `post_id` | String |


### Comment Collection:
| Key | Type |
| --- | --- |
| `Document ID` | String |
| `user_id` | String |
| `post_id` | String |
| `text` | String |
| `created_at` | String |
    





