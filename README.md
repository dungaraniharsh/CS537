# CS537
Ads Log Storage using DApp

Digital advertising, particularly ads into log files on video streams, has had a rapid growth over the last few years. In this research, we propose an integrated blockchain and IPFS framework to securely store, share and tamper-proof ads into log files for DVEO, which is a leader in delivering videos and ads over IP. To maintain the scalability and efficiency, we do not directly store the log file on the blockchain. Instead, we utilize IPFS to store log file. Then we hash the log file using the IPFS Merkle DAG structure and store the hash on the blockchain. We designed a smart contract to store and access these hashes on the blockchain. This smart contract is computationally simple to use, store, and access into log file. The framework we developed provides DVEO with a scalable, cost-effective, and tamper-proof system that has been customized for the organization. The proposed solution can be used to securely store and share sensitive data and can guarantee that the data remains immutable.


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

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

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.