# retype00

#npm init 
#npm install retypeapp-win-x64


in package json write:

{
  "scripts":
  {"start":"retype watch",
   "build":"retype build"
  },
  "dependencies": {
    "retypeapp-linux-x64": "^2.2.0"
  }
}

#comand npm run start
#comand npm run build

# inside netlify:
- CI= npm run build
- folder build(see in static fix compiling)