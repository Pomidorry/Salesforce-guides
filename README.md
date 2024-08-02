# Salesforce portfolio guide :shipit:

## Short overview 📜
> Here you can a clear step-by-step guide with detailed explanation and screenshot to each step how to create personal web site to showcase your accomplishments on Salesforce

## Why implement this project ❔
- [x] Additional opportunity to practice your designing skills
- [x] New item for pet-project portfolio for beginner Salesforce enjoyers
- [x] Non-trivial CV representation

## Let's start 🏁

### Prerequisite:
> You need to have you Salesforce org created (it can be **Trailhead Playground**, this one is free 💸)

### Let's move to main steps
1. Launch your (in my case) **Trailhead Playground**, find gear icon and go to Service Setup
![1p](https://github.com/user-attachments/assets/9d5fc2e1-0f0b-4853-b685-f2abac802e8f)

2. In Quick Find field search and select **Digital Experiences** (Settings), select **Enable Digital** Experiences checkbox and click the "Save" button
![2p](https://github.com/user-attachments/assets/cfb5f828-01a6-405f-80f4-68647fab5b97)

3. Then select **Digital Experiences** (All Sites) tab and click **New** to create new site
![2p](https://github.com/user-attachments/assets/68a7398c-0789-4d46-8edf-a32b5ed6a34d)

4. Choose **Customer Account Portal** template
![2p](https://github.com/user-attachments/assets/b7626ad2-e76a-429b-a1b9-29ab121d0fdb)

5. Click **Get Started** button
![2p](https://github.com/user-attachments/assets/3f730161-5dee-45b3-a18f-e5c1e36f6c7a)

6. Enter site name and URL. URL will look like this https://mycompany-dev-ed.develop.my.site.com/[customurlname]. Then click **Create**. Your site has been created in Preview status, which means that what you have created isn’t in the world yet.
![2p](https://github.com/user-attachments/assets/f0510be9-a744-41ed-b00b-159cff816bf9)

7. In **My Workspace** form select **Builder** tool
![2p](https://github.com/user-attachments/assets/162aa2c4-7fc2-46ee-9795-44b45d087bc1)

8. You can see default picture on your layout. Click it once. You will see the element name (**Rich Content Editor**)
![2p](https://github.com/user-attachments/assets/e7fac7eb-4529-4f18-986a-f4e401d7ef16)
Click it one more time. You'll see tool panel like this
![2p](https://github.com/user-attachments/assets/0f2ccc18-454a-4dc3-a193-f06fe9e1b4d9)
Now you can edit your portfolio header at your discretion e.g.
![2p](https://github.com/user-attachments/assets/9b8765e8-be9b-4e23-9def-a473d2f1cf02)

9. In **Theme** tab you can customize site basic colors, your logo image, set fonts and play with your site appearance settings 
![Untitled](https://github.com/user-attachments/assets/683701f1-4470-44cb-965e-64bd72417c43)

10. On the **Home** tab, click the down arrow next to the **Page Properties** gear icon, select **New Page** at the bottom of the menu
![Untitled](https://github.com/user-attachments/assets/1c7e5273-d870-40da-9059-2499c5625947)

11. Choose **Standard Page**
![image](https://github.com/user-attachments/assets/433830bf-7bb0-45a7-96b6-4ebc411a6de7)

12. Choose **Flexible Layout** and click **Next**
![Untitled](https://github.com/user-attachments/assets/b0a4274d-2cd3-4e20-b371-9d8f3ef1e103)

13. Enter page name and then click **Create** to add new page
![Untitled](https://github.com/user-attachments/assets/d3f5723c-f591-4cb8-8406-4b17e90f3892)

14. Now you can find your brand new page in page search
<br>![Untitled](https://github.com/user-attachments/assets/29c3b34d-52b4-4044-be00-f8eeeb3e75f4)</br>

15. But now you are on just created page. Let's edit your nav menu so you navigate your site quickly. Click you navigation menu and then click **Edit Default Navigation** button in opened form
![Untitled](https://github.com/user-attachments/assets/7e285808-04ac-42b0-9b2f-e15c4ac049cc)

16. Click **Add Menu Item** button. Then enter page name, select **Site Page** type, and select **Publicaly available** checkbox. You can remove elements from the menu structure (like on 5th action on the screenshot)
![Untitled](https://github.com/user-attachments/assets/1bd5f06f-37cd-47bf-8e8d-9a0e042caf61)

17. Now you can create and add to nav menu structure any page you want (it can be section about your education or experience) the same way

18. Let's come back to home page. You should know that you can do the same thing in the **Tile Menu**. Just click the **Tile Menu** area. Select **Default Navigation** in **Default Menu** field. Click **Edit Default Navigation** and you will see form like in 16th step. 
![Untitled](https://github.com/user-attachments/assets/f5febf1a-e01c-456b-ac24-23882449b265)

> [!NOTE]
> The only difference between these two methods - in the second case you will have navigation links both from **Tile Menu** and **Navigation Menu**

19. Remove **Record List** and **Paused Flow** clicking **Recycle Bin** icon if you don't need them. You can remove all components this way
![Untitled](https://github.com/user-attachments/assets/6ff70942-4081-47b2-8659-1621adcf748e)

20. In this tutorial I'll work with **Rich Component Editor** from **Component** tab. You can also add different components for analytics, file managment etc. You can learn more about them via [Components in Experience Builder](https://help.salesforce.com/s/articleView?id=release-notes.rn_experiences_components.htm&release=244&type=5) article
<br>![Untitled](https://github.com/user-attachments/assets/36c92b81-da4b-4c22-aaca-4e3eb8a8b4d0)</br>

21. But now let's move to **About me** page and drag **Rich Component Editor** to Column 1
![Untitled](https://github.com/user-attachments/assets/d6bc205e-ef10-49a3-a1e3-89970ac22a33)

> [!NOTE]
> You also can select any **Column Layout** from list
![Untitled](https://github.com/user-attachments/assets/1f4577db-761d-4a55-aabf-491dba946515)

> [!NOTE]
> You can add more then one component to the section

22. Fill your page sections with information about you. Here you can see sample of section
![image](https://github.com/user-attachments/assets/6308ddf4-75cf-4664-a392-05a8a698d351)

23. You can also highlight word (or colocation) and click link button to make hyperlink. Can be userd to add you social media links
![Untitled](https://github.com/user-attachments/assets/48c7d962-56f2-41f4-8729-9eccb0a0180a)

24. Let's look at our result. In the top bar you can see **Preview** button. Ckick it to see how user will see your site
![Untitled](https://github.com/user-attachments/assets/fcea6a89-adc7-48be-af9e-514e12d5240d)

25. Now you completed with filling content and now we need to publish you site and make it available for everyone. Let's change settings. Select **Public Access** checkout
![Untitled](https://github.com/user-attachments/assets/9008db4e-d7d7-42de-93e7-a1299862c15f)

26. Finally the last step. Publish your site clicking this button **Publish**
<br>![Untitled](https://github.com/user-attachments/assets/abc58d6e-1f0d-40fa-8404-9cabeb200935)</br>

Your URL should look similar to this: https://brave-wolf-ksa17a-dev-ed.trailblaze.my.site.com/Portfolio/s/

## My result 👨‍💻
> You can see it [here](https://empathetic-bear-q8q2h2-dev-ed.trailblaze.my.site.com/s/). I'm sure, you can create much better design but it is just a sample :trollface:

## Source :basecamp:
> Tutorial is based on [Trailhead project](https://trailhead.salesforce.com/content/learn/projects/build-your-personal-portfolio-on-salesforce)
