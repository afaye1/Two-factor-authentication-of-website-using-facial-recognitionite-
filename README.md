# Two-factor-authentication-of-website-using-facial-recognition-

Description: This project explains a new graphical password scheme to provide security to confidential
data for different sites by providing a Keyword that is more resilient to Cyber Attacks like phishing and man in the middle attacks.
Technologies Used:-Servlets, MYSQL, HTML, Java Script.


![1](https://user-images.githubusercontent.com/25890584/74859076-5cd2ed80-5314-11ea-962b-2d91cb59edd8.png)


Work Flow:
1. The image of a person is taken during signup

![2](https://user-images.githubusercontent.com/25890584/74859079-5d6b8400-5314-11ea-8d47-4f931e4b748d.png)

2. during login, we will validate the details given at the sign-up. An image is taken during log-in and will compare with the image give on sign-in. After validating both the images the person will gets logged-in.

![3](https://user-images.githubusercontent.com/25890584/74859081-5d6b8400-5314-11ea-96f7-fc808016a9bd.png)


Used Keras API for identifying person in an image frame. Used opencv to modify the image to the required format to feed the deep neural network layer. Deployed the model using Flask framework. 


References:
1.https://scholarcommons.scu.edu/cgi/viewcontent.cgi?article=1110&context=cseng_senior
2.https://github.com/ageitgey/face_recognition
3.https://github.com/susantabiswas/facial-login-web
