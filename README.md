<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">-
<Title>Form Without Semantic HTML</title>
</head>
<body>
<h1>Form Without Semantic HTML</H1>
<Form>
<label for="FullName">Full Name:</label>
<input type="text" id="fullName" name="fullName" required>

<label for="email">Email:</label>
<input type="email"id="email"name="email" required>

<label for="password">Password:</label>
<input type="password" id="password"name="passsword" required>

<label for="gender">Gender:</label>
<select id="gender" name="gender">
   <option value="male">Male</option>
   <option value="female">Female</option>
   <option value="other">Other</option>
   </select>

 <label for="Newsletter">Subscribe To Newsletter:</label>  
 <input type="checkbox" id="Newsletter"name="Newsletter" required>

 <label for="comments">Comments:</label>
 <textarea id="comments" name="comments" rows="4"></textarea>

 <button type="submit">Submit</button>
 </form>

 </body>

 </html>