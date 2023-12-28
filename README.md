<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Virtual Bookshelf: Flask Website with SQLite Database Integration</strong></p>
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Overview</strong></p>
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>the Virtual Bookshelf project the process of seamlessly integrating an SQLite database into a Flask website, creating a virtual bookshelf accessible at <strong>localhost:5000</strong>. In this project, you will learn how to perform essential CRUD (Create, Read, Update, Delete) operations on the database, allowing you to manage your personal library with ease.</p>
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Installation</strong></p>
<ol style="margin-bottom:0cm;margin-top:0cm;" start="1" type="1">
    <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Clone the repository:</li>
</ol>
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; git clone <a href="https://github.com/Siya016/Virtual-Bookshelf.git">https://github.com/Siya016/Virtual-Bookshelf.git</a></p>
<ol style="margin-bottom:0cm;margin-top:0cm;" start="2" type="1">
    <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Navigate to the project directory:</li>
</ol>
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; cd Virtual-Bookshelf</p>
<ol style="margin-bottom:0cm;margin-top:0cm;" start="3" type="1">
    <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Install dependencies:</li>
</ol>
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; pip install -r requirements.txt</p>
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Tech Stack</strong></p>
<ul style="margin-bottom:0cm;margin-top:0cm;" type="disc">
    <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Flask</strong>: A lightweight web framework for Python.</li>
    <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>SQLite</strong>: A serverless, self-contained, and zero-configuration database engine.</li>
</ul>
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Project Structure</strong></p>
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>The project structure is organized as follows:</p>
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:18.0pt;font-size:11.0pt;font-family:"Calibri",sans-serif;'>.</p>
<ul style="list-style-type: disc;">
    <li><strong>add.html</strong>: Template for adding new books.</li>
    <li><strong>index.html</strong>: Template for displaying the book list.</li>
    <li><strong>edit_rating.html</strong>: Template for editing book ratings.</li>
    <li><strong>__init__.py</strong>: Initialization file for the Flask application.</li>
    <li><strong>main.py</strong>: Main application file.</li>
    <li><strong>book.db</strong>: SQLite database file.</li>
    <li><strong>requirements.txt</strong>: List of dependencies.</li>
    <li><strong>README.md</strong>: Project documentation.</li>
</ul>
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>CRUD Operations</strong></p>
<ul style="margin-bottom:0cm;margin-top:0cm;" type="disc">
    <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Create (C):</strong>
        <ul style="margin-bottom:0cm;margin-top:0cm;" type="disc">
            <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Add new books to the library using the Flask application.</li>
        </ul>
    </li>
    <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Read (R):</strong>
        <ul style="margin-bottom:0cm;margin-top:0cm;" type="disc">
            <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Retrieve and display the list of books in the library.</li>
        </ul>
    </li>
    <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Update (U):</strong>
        <ul style="margin-bottom:0cm;margin-top:0cm;" type="disc">
            <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Modify existing book details in the library.</li>
        </ul>
    </li>
    <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Delete (D):</strong>
        <ul style="margin-bottom:0cm;margin-top:0cm;" type="disc">
            <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Remove books from the library.</li>
        </ul>
    </li>
</ul>
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Visit <strong>http://localhost:5000</strong> in your web browser to access your virtual bookshelf.</p>
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Features</strong></p>
<ul style="margin-bottom:0cm;margin-top:0cm;" type="disc">
    <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Add Books:</strong>
        <ul style="margin-bottom:0cm;margin-top:0cm;" type="disc">
            <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Easily add new books to your virtual library.</li>
        </ul>
    </li>
    <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>View Book List:</strong>
        <ul style="margin-bottom:0cm;margin-top:0cm;" type="disc">
            <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Access a comprehensive list of all the books in your library.</li>
        </ul>
    </li>
    <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Check Library Status:</strong>
        <ul style="margin-bottom:0cm;margin-top:0cm;" type="disc">
            <li style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>See if your library is empty or populated with books.</li>
        </ul>
    </li>
</ul>
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:0cm;font-size:11.0pt;font-family:"Calibri",sans-serif;'>&nbsp;</p>
