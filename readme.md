# typings
$typings install redux=https://raw.githubusercontent.com/andrew-w-ross/typings-redux/master/redux.d.ts  --save
redux
`-- (No dependencies)


$ typings install react-redux --save
typings WARN badlocation "github:andrew-w-ross/typings-redux" is mutable and may change, consider specifying a commit hash
typings INFO reference Stripped reference "https://raw.githubusercontent.com/andrew-w-ross/typings-react-redux/21202533f75a73d4fa4c50e0357aaf23739fcabb/typings/main.d.ts" d
uring installation from "react-redux" (main)
react-redux
`-- redux

# tslint
1. install tslint vscode integration
2. switch on tslint by File->Preferences->Settings->Workspace Settings-> settings.json
`{ "tslint.enable": true }`
you get an error from vscode output saying
 To use TSLint in this workspace please install tslint using 'npm install tslint' or globally using 'npm install -g tslint'.
You need to reopen the workspace after installing tslint.
3. npm install --save tslint and reopen the workspace