# Collabarative Code Editor
* multiple users can join a room for simultaneous editing in realtime.
* single user creates a room.
* user who created/joined the room can share the room ID for invite.

## Tech Stack
* websockets used for realtime data streaming.
* React used in frontend and Node.js in backend.
* react-hot-toast used for notification.
* uuid library for generating random long string for using as Room ID.
### Production
* first add the env variable value to platform used for deployment of client code.
* use "REACT_APP_WEB_SOCKET_URL" key name and assign server code production url as value.
* in client, run "npm run build" for test run.
* in deployment platform for client code, select the client as "root folder".
* NOTE: above step is not required in case if manually hosting on server
  
# IMAGES OF WEBSITE
IMAGE 1 : 
![collab 1](https://github.com/utkarshtipre2002/Collaborative_code_editor/assets/115633331/38f1db85-1e88-4ecf-86d5-4147850c8f88)

IMAGE 2: 
![collab 2 ](https://github.com/utkarshtipre2002/Collaborative_code_editor/assets/115633331/d153bb5f-522f-4bac-bfe3-9d2770821cc7)

IMAGE 3: 
![collab 3](https://github.com/utkarshtipre2002/Collaborative_code_editor/assets/115633331/f6d863f1-f967-47c7-a356-9ca1aefcf0b5)

IMAGE 4: 
![collab 4](https://github.com/utkarshtipre2002/Collaborative_code_editor/assets/115633331/aab3e59d-579c-4fb6-97be-dba7a0342d6c)

IMAGE 5: 
![collab 5](https://github.com/utkarshtipre2002/Collaborative_code_editor/assets/115633331/dabc8720-092f-4233-9208-f45e418f4a4c)

IMAGE 6: 
![collab 6](https://github.com/utkarshtipre2002/Collaborative_code_editor/assets/115633331/24853e8d-0431-4681-9034-808249368d72)







