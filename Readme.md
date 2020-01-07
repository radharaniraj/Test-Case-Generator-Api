This application allows user to generate variety of test cases for diffrent types of Codding *Problems*
<br><br><br>Currently it can generate test cases for: <br>
<b>
1 . Strings <br>
2 . Arrays <br>
3 . Numbers <br>
</b>

You can start the server by running the index.js file <br>
*npm install*<br>
*node index.js*<br>
Server will start on <b>http://localhost/3000</b><br>


<table style="width:100%">
  <tr>
    <th>Feature</th>
    <th>Method</th>
    <th>Endpoint</th>
    <th>Input body</th>
  </tr>
  <tr>
    <td>Random Numbers</td>
    <td>Post</td>
    <td>/numbers</td>
    <td>{testcases: "",min: "", max: ""}</td>
  </tr>
  <tr>
    <td>Random Arrays</td>
    <td>Post</td>
    <td>/arrays</td>
    <td>{testcases: "",minelement: "", maxelement: "",arraysize: ""}</td>
  </tr>
  
  <tr>
    <td>Random String</td>
    <td>Post</td>
    <td>/string</td>
    <td>{testcases: "",stringsize: "",chars:""}</td>
  </tr>
</table>


