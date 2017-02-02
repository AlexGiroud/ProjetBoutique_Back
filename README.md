# `ProjetBoutique` — AngularJS FrontEnd 

This project is realised as a school projet (Ynov Lyon / Ingesup) by Alexandre Vladovich & Alexandre Giroud-Bit.
The code is licenced under GNU GPLv3.

## Install and run

To get you started you can simply clone the `ProjetBoutique` repository and install the dependencies:

### Prerequisites

You need git to clone the `ProjetBoutique_Back` repository. You can get git from [here][git].

We also use a number of Node.js tools to initialize and test `ProjetBoutique`. You must have Node.js
and its package manager (npm) installed. You can get them from [here][node].

### Clone `ProjetBoutique_Back`

Clone the `ProjetBoutique_Back` repository using git:

```
git clone https://github.com/AlexGiroud/ProjetBoutique_Back.git
cd ProjetBoutique_Back
```

### Install Dependencies

We have two kinds of dependencies in this project: tools and Angular framework code. The tools help
us manage and test the application.

* We get the tools we depend upon via `npm`, the [Node package manager][npm].



```
npm install
```

### Run the Application

We have preconfigured the project with a simple development web server. The simplest way to start
this server is:

```
cd ProjetBoutique_Back
node .
```

Now browse to the app at [`localhost:3000/`][local-app-url].
The API endpoints are located at [`localhost:3000/api/`][local-api-url]
We have provided an API explorer located at [`localhost:3000/explorer/`][local-explorer-url]
