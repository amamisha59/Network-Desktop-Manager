# Network-Desktop-Manager
Interact with server/client and perform some operations on the client (request for help) or server (create some folder, rename, file share and message ).    
<h2>Project Description:</h2>
<ol>
  <li><b>Client-Server Model: </b>The project implements a simple client-server model where the server listens for client connections and responds to various requests sent by the client.</li>
  <li>Functionality:</li>
  <ul>
    <li>
      <b>New Folder Creation:</b> The client can request the server to create a new folder by providing a folder name. The server then creates the new folder and logs the location where it is added.
    </li>
    <li>
      <b>Folder Renaming:</b> The client can request the server to rename a folder by providing the old and new folder names. The server renames the folder and logs the location where the renaming happens.
    </li>
    <li>
      <b>File Transfer:</b> The client can request the server to transfer a file by providing the file name. The server sends the specified file to the client, and both the server and client log the location where the file is saved.
    </li>
    
  </ul>
  <li>Communication Protocol:<br>
  Communication between the client and server is achieved through ObjectInputStream and ObjectOutputStream, allowing the exchange of Java objects.
  </li>
</ol>
<h2>output</h2>
<img src="https://github.com/amamisha59/Network-Desktop-Manager/blob/main/Screenshot%20(160).png" alt="output1" style="height:200px;width:700px">
<img src="https://github.com/amamisha59/Network-Desktop-Manager/blob/main/Screenshot%20(162).png" alt="output1" style="height:200px;width:700px">
<h2>Conclusion</h2>
<ul>
  <li>The project provides a foundation for a file and folder management system over a local network.</li>
  <li>It demonstrates the use of Java Socket programming for communication between a client and a server.</li>
</ul>
