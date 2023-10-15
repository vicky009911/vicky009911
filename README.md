<!Doctype html>
<html>
  <head>
    <title>Personal info</title>
    </head>
  <body>
    <form>
    <label>Name:</label>
    <input type="text" name="name" size="15"/><br>
      <br>
      <label>Paragraph:</label><br>
      <textarea cols="40" row="20" value="paragraph">
        </textarea><br><br>
      <label>
        Gender:
      </label><br>
      <input type="radio" name="gender">Male<br>
     <input type="radio" name="gender">Female<br>
  <input type="radio" name="gender">Other<br>
      <br>
      <label>Number:</label>
      <input type="number" id="number" name="number" min="0" max="6"><br><br>
      <label>Select file</label>
      <input type="file" id="myfile" name="myfile"><br><br>
      <label>Profession:</label>
      <select>
        <option value="student">Student</option>
        <option value="parent">Parent</option>
        <option value="teacher">Teacher</option>
        </select><br><br>
      <input type="submit" value="submit">
      </form>
      </body>
      </html>
