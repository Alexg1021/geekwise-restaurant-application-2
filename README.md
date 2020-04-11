##Instructions
This version of the restaurant project is set up to use CDNs and the instructions under **Quickly Try JSX** for more information.  at [this link](https://reactjs.org/docs/add-react-to-a-website.html#add-jsx-to-a-project):
https://reactjs.org/docs/add-react-to-a-website.html#add-jsx-to-a-project



###Frameworks and Libraries:
Bootstrap and ReactJS per the instructions and recommendations in the assignment. Although the project is not set up to be production-ready, using CDN's instead of local installlations of Node, Bootstrap, and React make for a lighter, experience requiring less waiting time and bandwidth from the user.

##Other Documentation
Following are some troubleshooting notes that might be helpful for scaffolding, which will provide access to Jest, a testing framework for ReactJS:

- NVM is your friend. Install it if you don't have it, and use it to make sure you are installing new versions of Node and NPM. There is more information here.

- If the normal installation instructions for React do not work, try the instructions on this page.

- If all else fails, uninstall Node and the packages that were giving you errors and warnings that blocked other installations. Then reinstall them. If you decide to uninstall NPM, do that last because you need it to uninstall and reinstall the other packages. 

- You can install a new NPM using the curl command. I uninstalled NPM too early and had to search for the curl command sequence on the Internet.

- The troubleshooting of uninstalling, reinstalling, and restarting with scaffolding looked something like this:

		$ npm uninstall -g create-react-app
		$ npm uninstall -g yarn
		$ npm cache clean --force
		$ npm install -g
		$ create-react-app my-app
		$ npm install yarn
		$ npm init
		$ create-react-app my-app
		$ cd my-app
		$ yarn start (per instructions in terminal, but you can also use npm start)

At that point you should be connected to a Git repo and a Node server will start on localhost. The web page will show up on the localhost noted in your terminal message.

#### Developer's Notes:
- I should have considered React Native more seriously. I was particularly impressed that ARIA standards were built-in. When I started, I didn't think I had enough time to take on the React Native learning curve, but the debugging might have been the same.With the amount of debugging I had to to to get my machine to stop "updating" to Node 8.x instead of 13.X, 

- In the future, I would most likely scaffold [from here](https://github.com/facebook/create-react-app#create-react-app-- ). I would use Jest for testing since it has a template to test basic rendering. I also would have started the main rep with project folders and created branches when I had improvements to make.

- I thought it might be more efficient to use hot links go from page to page, but I am considering letting the pages be components in React. There is also a [Native navigation library](https://reactnavigation.org/docs/hello-react-navigation/) at https://reactnavigation.org/docs/hello-react-navigation/ that piqued my interest in the Native library.