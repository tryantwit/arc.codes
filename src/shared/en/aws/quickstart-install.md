# Installation

Open up a terminal and create a project folder:

```bash
mkdir testapp
cd testapp
npm init --yes
npm install @architect/architect
touch .arc
```

And then paste the following contents into the `.arc` file:

```arc
@app
testapp

@http
get /
```

Run `npx create` and check out the fresh new app.

Congrats, you've successfully set up and deployed a serverless web app! Nice work. 💖

## Next: [.arc project layout](/quickstart/arc-project-layout)
