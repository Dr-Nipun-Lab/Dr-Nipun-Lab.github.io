---
title: "Publications"
permalink: /publications/
layout: single
---

# Publications

Below is the complete list of publications from Dr. Nipun Lab.  
Click anywhere in the table to open the Google Drive folder containing all PDF files.

👉 **[Click here to access full PDF archive](https://drive.google.com/YOUR_FOLDER_LINK)**

---

<table>
  <thead>
    <tr>
      <th>Title</th>
      <th>Authors</th>
      <th>Journal</th>
      <th>Year</th>
    </tr>
  </thead>
  <tbody>
    {% for p in site.data.publications %}
    <tr onclick="window.location='https://drive.google.com/YOUR_FOLDER_LINK';" style="cursor:pointer;">
      <td>{{ p.Title }}</td>
      <td>{{ p.Authors }}</td>
      <td>{{ p.Journal }}</td>
      <td>{{ p.Year }}</td>
    </tr>
    {% endfor %}
  </tbody>
</table>

<style>
table {
  width: 100%;
  border-collapse: collapse;
}
th, td {
  padding: 10px;
  border: 1px solid #ccc;
}
tr:hover {
  background-color: #eef7ff;
}
</style>
