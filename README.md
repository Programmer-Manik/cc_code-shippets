{
  "react component": {
	"prefix": "cc",
	"body": [
		"const ${TM_FILENAME_BASE/(.*)/${1:/pascalcase}/} = () => {",
		"  return (",
		"    <div>",
		"      <h2>Welcome to the ${TM_FILENAME_BASE/(.*)/${1:/pascalcase}/} page</h2>",
		"    </div>",
		"  );",
		"};",
		"",
		"export default ${TM_FILENAME_BASE/(.*)/${1:/pascalcase}/};"
	],
	"description": "React Functional Component Template"
   }
 }
