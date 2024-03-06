# Streaming Avatar Demo

## Pre-Requisites

- Node.js and npm installed on your system.
- API key for HeyGen's API or Trial Token

## Run the Demo

1. Clone the repository.

   ```
   git clone https://github.com/HeyGen-Official/StreamingAvatar.git
   ```

2. Open the `index.js` file and replace `'YourApiKey'` with your API key:

   ```
   "apiKey": "YourApiKey";
   ```
3. (optional) Open the `server.js` file and set your OpenAI API key to use talk mode:
   ```
   const openai = new OpenAI({
     apiKey: "<your openai api key>",
   });
   ```

4. open a terminal in the folder and then install the express and run the server.js:

   ```
   npm install express
   node server.js
   ```

5. you will see `App is listening on port 3000!`.

## Use the Demo

0. Make sure you are whitelisted to use the HeyGen's Streaming avatar API.
1. Open the web browser and enter the `http://localhost:3000`to start the demo.
2. Click the "New" button to create a new session. The status updates will be displayed on the screen.
3. After the session is created successfully, click the "Start" button to start streaming the avatar.
4. To send a task to the avatar, type the text in the provided input field and click the "Repeat Text" button.
5. In order to use Talk mode, set your **OpenAI** key in **server.js** before starting the server and click "Talk" button
6. Once done, click the "Close Connection" button to close the session.

Remember, this is a demo and should be modified according to your needs and preferences. Happy coding!

## Troubleshooting

In case you face any issues while running the demo or have any questions, feel free to raise an issue in this repository or contact our support team.

Please note, if you encounter a "Server Error", it could be due to the server being offline. In such cases, please contact the service provider.
