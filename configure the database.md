##### **Step 1: Create Your Free Database**

Go to https://firebase.google.com and sign in with your Google account.



Click Go to console (top right) and then click Create a project.



Name it something like my-personal-archive.



You can turn off Google Analytics for this project (you won't need it), and click Create project.



##### Step 2: Set up Firestore (The Database)

Once your project is ready, look at the left-hand menu. Expand the Build section and click on Firestore Database.



Click the Create database button.



It will ask about security rules. Select Start in Test mode (this allows your app to read and write data easily while we get it working).



Choose a location closest to you and click Enable.



Step 3: Get Your Connection Keys

Go back to your Project Overview (click the home icon or "Project Overview" at the top left).



In the center of the screen, you will see an icon that looks like </> (this stands for Web). Click it.



Give your web app a nickname (like ArchiveWeb) and click Register app.



Firebase will now show you a block of code. Look for the part that looks exactly like this:



*JavaScript*

*const firebaseConfig = {*

&#x20; *apiKey: "YOUR\_API\_KEY",*

&#x20; *authDomain: "YOUR\_PROJECT.firebaseapp.com",*

&#x20; *projectId: "YOUR\_PROJECT",*

&#x20; *storageBucket: "YOUR\_PROJECT.appspot.com",*

&#x20; *messagingSenderId: "123456789",*

&#x20; *appId: "YOUR\_APP\_ID"*

*};*

Copy that specific firebaseConfig block and paste it here for me. Would you like me to write the final V6 code integrating your database so your archive instantly syncs across all your devices?

