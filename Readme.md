<table border="1" cellspacing="0" cellpadding="8">
  <tr>
    <th>Method</th>
    <th>Return Type</th>
    <th>How Many Documents</th>
    <th>Example</th>
  </tr>
  <tr>
    <td><b>find()</b></td>
    <td>Array</td>
    <td>একাধিক ডকুমেন্ট (যতগুলো কন্ডিশনের সাথে মিলে)</td>
    <td><code>db.users.find({ city: "Dhaka" })</code></td>
  </tr>
  <tr>
    <td><b>findOne()</b></td>
    <td>Object</td>
    <td>শুধু একটি ডকুমেন্ট (প্রথম যেটা মিলে)</td>
    <td><code>db.users.findOne({ city: "Dhaka" })</code></td>
  </tr>
</table>
