# ZikoDB 

## Syntaxe
```js
 const Db1 = new Db('Data1');
async function main() {
    const students = await Db1.getDoc('students')
    await students.write('student_name', { notes: ["13","17"] })
    await students.save();
    }
main();
``` 

<!-- 
add gui ? 
rename
 -->