# Kanban WebApp

Kanban board webapp to utilize as a todo list. Creating the front-end with React and to test the backend with different languages and frameworks by version.

## Links
+ [Github Repo](https://github.com/NewIncome/kanban)
+ [Front-end design with Figma](https://www.figma.com/file/h1R24kAd9kHowfrysVbQuF/Kanban.v1)


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)


<!--  PLANNING

// to implement: Categories(dropDown): Work, Personal, House/Chores, Social/Fun
// to implement: This Week(dropDown): Month, another week, anoter Month
> Base Categories to View
List All | Due | Upcoming | This Week |	Done		(5), (all:8)
						/			  \
				| Fresh | Doing | Done |

> Filters:
  -All, -Date(past, thisWeeks, nextWeeks+),
  -ThisWeeks(status: done, doing, blanc)
  -All+Done

> Store
  -store=[{},{},...]; each {} is a task
  -each Ta, has the following properties/keys: name, details, date, status,
> Basic demo store info
	[
	  {
	    name: '',
	    details: '',
	    status: 'blanc',
	    dateCreated: '',
	    dateDue: '',
	    date2work: '',
	  },
	]
> Components + Props
  -Board(base) > Props: store	=> = it's state
  -Column s > Props: title:'', tasks:[{},...]	=> = it's state
  -Task s > Props: ...details...	=> = it's state

 -->