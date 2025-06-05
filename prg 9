const fs = require("fs");
const createFile = (fileName, data) =>
{
fs.writeFile(fileName, data, (err) =>
{
if (err)
{
console.error("Error creating file:", err);
} 
else
{
console.log("File created successfully");
}
});
};
//createFile("example.txt", "This is a sample text file");
const readFile = (fileName) => {
fs.readFile(fileName, "utf8", (err, data) => {
if (err) {
console.error("Error reading file:", err);
} else {
console.log("File content:");
console.log(data);
}
});
};
//readFile("example.txt");
const appendFile = (fileName, newData) =>
{
fs.appendFile(fileName, newData, (err) =>
{
if (err) 
{
console.error("Error appending to file:", err);
} 
else
{
console.log("Data appended to file successfully");
}
});
};
//appendFile("example.txt", "In Additional data appended");
const updateFile = (fileName, newData) =>
{
fs.writeFile(fileName, newData, (err) =>
{
if (err)
{
console.error("Error updating file:", err);
}
else
{
console.log("File updated successfully.");
} 
});
};
//updateFile("example.txt", "This is updated content");
const deleteFile = (fileName) =>
{
fs.unlink(fileName, (err) =>
{
if (err)
{
console.error("Error deleting file:", err);
} 
else
{
console.log("File deleted successfully.");
}
});
};
// deleteFile("example.txt");
