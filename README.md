
# CAREitable - Charities & Donations


CAREitable makes it super easy for you to make cash & non-cash donations from the convenience of your house. Don’t we all have a lot of clothes, books, and other household goods just lying at some corner and getting dusted. It’s time to give them a new life by donating them to those who in need and bring smiles on their faces!! Your donations will bevisible to all the local NGOs like orphanages, old age homes etc. The owner of these NGOs can directly contact you and schedule a pickup.



## What it can do?
People nowadays have become more and more busy in their lives that they forgot about giving back to the society. Even if they wanted to donate they couldn't as they fear that the donations would go to right hands. They also did not want to get out from their comfort zones and look for local NGS to donate to. To solve this problem, Our app can provide various solutions to these individuals. Using our app donors can post any item they want to donate with detailed images and description. Their donation listing will  be visible to thier local NGOs or any other location they want to post. The NGO owners can then contact these donors from thier listing to schedule a pickup.
## How we built it?


We built this app using Android Studio and integrated it with Firebase. 

Cloud Firestore is used in our app to save and retrieve user and the donation posts 
data. Firestore transactions are used to perform batch write and read operations
on various activities of the app like in post creation and deletion.
We have also used Firestore indexing to orderby and filter content.
 
 We have used Firebase Authentication to handle the User Registration/Login
activity of the app which enable secure and flexible user verification.

Cloud Firestore is used to store media files such as post’s images.

Our app is designed following Google's Material Design Guidlines and practices. Various Material components are used throughout the app.
## Future of CAREitable.

Charity Section where donors can directly donate money online to national NGO’s, 
Fundraisers, Government Humanitarian schemes etc.


More Verified account system where donors and receivers are well examined and
verified by our system by aadhar linking, NGO certificates. 


Delivery Service provided by us to eliminate the need to physically reach the donor
which raises privacy and safety concerns. It would also increase the 
range of our services to more and more people.

Smart Categories pr which will give a more personalized fields to be filled by the donor
according to the catergory. Like for Food item fields like expiry date, type. Size and Gender
for clothes etc
