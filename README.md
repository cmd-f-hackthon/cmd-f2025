# cmd-f 2025 

# Eva, Jenny, Ruiyang, and Linda

 Project description goes here...


 In the `frontend/.env.local` add 
 ```
 NEXT_PUBLIC_GOOGLE_MAPS_API_KEY=YOUR-API-KEY
 ```

 And in the `backend/.env` add
 ```
 PORT=4000
 MONGODB_URI=
 GOOGLE_MAPS_API_KEY=
 ```

 In the terminal 1 to start the backend
 ```
 cd backend
 node src/index.js
 ```

 In the terminal 2 to start the frontend
 ```
 cd frontend
 npm run dev
 ```