<table border="1" cellspacing="0" cellpadding="8">
  <tr>
    <th>Method</th>
    <th>How Many Documents</th>
    <th>Workings</th>
    <th>Value of Return</th>
    <th>Example</th>
  </tr>
  <tr>
    <td><b>find()</b></td>
    <td>সব সময় একাধিক ডকুমেন্ট (records) রিটার্ন করে।</td>
    <td>কন্ডিশনের সাথে যতগুলো মিলে, সবগুলোই দেবে।</td>
    <td>রিটার্ন ভ্যালু হয় array আকারে।</td>
    <td><code>db.users.find({ city: "Dhaka" })</code></td>
  </tr>
  <tr>
    <td><b>findOne()</b></td>
    <td>শুধু একটা ডকুমেন্ট রিটার্ন করে।</td>
    <td>কন্ডিশনের সাথে যতগুলো মিলে প্রথম যেটা পাবে সেটাই রিটার্ন করবে।</td>
    <td>রিটার্ন ভ্যালু হয় object আকারে।</td>
    <td><code>db.users.findOne({ city: "Dhaka" })</code></td>
  </tr>
</table>
