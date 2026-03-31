# Internship-Assignments
1st assignment
const fs = require('fs');

const folderPath = './myFolder';

fs.readdir(folderPath, (err, files) => {
    if (err) {
        console.log("Error reading folder:", err);
        return;
    }

    console.log("Files in folder:");

    files.forEach((file) => {
        console.log(file);
    });
});
