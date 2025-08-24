# Intro to Software Tools

File Systems:
Becoming a successful programmer requires the ability to understand and work with the file system.

    Users
        Student
            Document
                class_notes.doc
                resources.doc
            workspace
                personal_website
                    favicon.ico
                    index.html
                    README.md
                    css
                        styles.css
                    img
                        logo.gif
                        header.jpg
                        photo.jpg
                    js
                        main.js

The path to main.js file is:

    /Users/student/workspace/personal_website/js/main.js

This is an **absolute path**.

In the above file system, imagine you want to specify the location of resources.doc from the student folder:

    ./Documents/resources.doc

The '.' is an **alias**, or shorthand, for the current working directory (student.student)

To move into a parent directory, you use '..'