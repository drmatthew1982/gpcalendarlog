# screenshots of gpcalendar 
(B/S based Gensolve's calendar functiion like system, we still discuss about which function can make most gp use and without redundant function)
### My friend ask me help for this project base on himself's needing, part time based on passion and friendship, a volunteer work without pay,previous year I focus on Massey MBA project and my friend also busy for his Physiological courses, and currently I busy for search a job..., but we will do best to ensure make progress (though maybe slowly)...
### This project still under MVP/POC phase, so many things such as code style documentation, annotation need be improved in the future after it become "stable"

### 2024 04 28, Finally I found a free server support the living-demo, but because the server is free, so it's also slow. (and the demo may stop at any time...)
### Here is the living-demo link:
http://drmatthew1982.serv00.net/

### it's seems simple now but will add more function after more requirement gathering
## Current this porject totally be public, We welcomed any advise and suggestions
### Here is the code reposity
##### The one Vue3 frontend can be used with both Spring boot backend and C#/.Net(8) backend
##### Considerate about the NZ market's skill stakes, we will try to add backend with other language as node.js and other frontend such as react.js
#### Spring boot backend
https://github.com/drmatthew1982/gpcalendarbackend
##### >>>>2024 04 06 support Client, Orginisation, Calender Event. Medical Report Management

#### C#/.Net(8) boot backend (Complete here means same performance as Spring boot end)
https://github.com/drmatthew1982/gpcalanderbackenddotnet_v8
##### >>>>2024 04 06 initial C# backend and completed login and load events to calender function
##### >>>>2024 04 09 Organisation Management Backend completed
##### >>>>2024 04 11 Client Management Backend completed
##### >>>>2024 04 13 Event Load Backend completed
##### >>>>2024 04 14 Event Creation and Update Backend completed
##### >>>>2024 04 14 Medical Record Management Backend completed
#### Vue3 frontend (Using Element plus, Typescript and full-calendar)
https://github.com/drmatthew1982/gpcalendarwebv3
#### ReactJS frontend (Using MUI, Typescript and full-calendar, link well be discolsed after finished)
https://github.com/drmatthew1982/gpcalendar_react
##### >>>>2024 04 20, after some research, we decide to use MUI (react-bootstrap has no tree view in current version and ,Fluent UI lack of OOTB layout, Element React is not good as Vue version)
##### >>>>2024 04 27 Management page Organisation data loading complete
##### >>>>2024 04 28 I found a free server is good for setup a living demo, so suspend react and focus on setup server in future days.
### By the way, I searching a job of senior software engineer at New Zealand provide by an Acredited Employer (I have legal work visa of New Zealand already),any one insterestd to me, please contact me
#### My LinkedIn profile:
https://www.linkedin.com/in/matthew-zhu-nz/
#### My Seek Profile:
https://www.seek.co.nz/profile/matthewyiqing-zhu-lqp3JrnbY5

## Following screen shot is current version of gpcalendar, it is improving contiously and pay the tech debt.
## (This system using Agile moethod for development, so evaluated from MVP and will be improved contiously).
### Following tasks/functions are finished:
  - Standalone architect (Spring boot + mybatis, Vue3 (Typescript) with extra plug-ins, MySQL)
  - Clients Management
  - Orginasations Management
  - Calendar (Utilised FullCalendar)
  - Appointments Management
  - Medical Records Management (Utilised Vue-drawing-canvas)
  - password encrypt
### Following tasks/functions in the plan list:
  - Export Appointments/Medical Records  as PDF
  - Normalizing code, such as exception handle, and component reuse in the frontend
  - Setup a living-demo (Done? At least it can use...)
  - Connect to ACC mamagement system
  - Admin Panel
  - UIUX improvement (espicially for Medical Records Management)
    -- 2024 Apr 06 update:  updated Medical Records Management's Image function)
  - User managerment/regiester (finished password change only)
  - OAuth2
  - Dockerilzation
  - Microservice version (for cloudilization in the future)
  - Partner/Employee functions
  - Other requirements from users
  - Necessary Code comments (good code can without comments, but speccial algorithm need)
## Screenshoot [Vue3+element-plus version]
### [Main View]
![8421706500351_ pic](https://github.com/drmatthew1982/screenshots/assets/9025958/ff4b950c-584e-45ae-9333-83b2334ff745)
### [Event Management]
![8431706500370_ pic](https://github.com/drmatthew1982/screenshots/assets/9025958/06cf1389-1543-4917-a6a1-e2f02877eed2)
### [Medical Record Management]
#### [Medical Record_older version]
![8441706500532_ pic](https://github.com/drmatthew1982/screenshots/assets/9025958/4af13e91-1db8-4c9a-bf42-80394f7ade4f)

#### [Medical Record new UX to let client more easly to understanding the panel functions]
<img width="1920" alt="图片" src="https://github.com/drmatthew1982/screenshots/assets/9025958/d64578b1-3ca8-4448-94c5-2be8597a02a1">

### [Orgnisation Management]
![8451706500554_ pic](https://github.com/drmatthew1982/screenshots/assets/9025958/67800971-3f49-4d2c-bb2b-95b4ad0afee1)
### [Client Management]
![8461706500571_ pic](https://github.com/drmatthew1982/screenshots/assets/9025958/03d4d9ef-5459-4aed-a694-f69b76eadf8d)
![8471706500583_ pic](https://github.com/drmatthew1982/screenshots/assets/9025958/c28f3e85-a1ec-4e20-8d18-3a9cf6d9d59b)
## Screenshoot [React+ MUI version]
### [Orgnisation Management] [ongoing now]
<img width="1920" alt="图片" src="https://github.com/drmatthew1982/screenshots/assets/9025958/2ccc717a-b652-4540-b21e-2aab4a1b3e7d">


