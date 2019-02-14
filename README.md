<p align="center">
  <img src="./img/TAB_logotype_orange.png" width="70%">
</p>

# 🛠 TAB Technical Challenge

Please build an app to showcase a small sample of some of the amazing work TAB has delivered over the years.

You are required to show the list of TAB case studies available [here](./endpoints/v1/caseStudies.json?raw=1). Please embed the URL below into your codebase. On launch, the app should always fetch the latest case studies from the given URL. If we add more case studies in the future, your app will display the up-to-date list. Do not read from hardcoded JSON.

**Fetch from the following URL:**
```
https://
```

# 👫 Requirements

The requirements are broken down into two [user stories](https://en.wikipedia.org/wiki/User_story):

* **TAB-001:** As a user, I want to see a list of case studies with an image and teaser.
* **TAB-002:** As a user, I want to read the full article when I select a case study from the list.

While completing these user stories, you may wish to commit your code to a local Git repository.

When you are done, please send via email the zipped up directory containing your project.

> ⚠️ Please do not push your work to a public repository.

If you make intermediate commits to a local repository, the most important thing is that you are proud of the code submitted at the end. Don't worry about the code cleanliness or robustness of earlier commits.

Please structure the code as you would for a production app that will be extended and maintained in the future. There is no need to leave comments in the code, as long as the code is self-documenting.

# 🔗 Example

You can see an example of how our case studies appear on the [TAB website](https://www.theappbusiness.com/work). However, we expect the user experience to vary between a mobile app and the website. Please put your own stamp on the project and make something the looks and feels great on the target operating system.

> ℹ️ A good place to start is to look at the JSON and the website together. You will see how the keys in the JSON relate to the content on the website. By doing this, you will see the keys that you will need to use to deliver your solution. There are additional keys in the JSON that you are not required to make use of.

# ✅ Acceptance Criteria

The acceptance criteria are intentionally vague, because we want to see your interpreation and your creativity.

## TAB-001

* Fetch/refresh the list of case studies from the URL provided.
* The user should see the list of case study articles as per the array value for the `"case_studies"` key in the JSON.
* For each article in the list, the hero image should be displayed in the list, available from the URL value provided for the `"hero_image"` key.
* For each article in the list, the teaser text should be displayed as per the `"teaser"` key in the JSON.

## TAB-002

* The user can navigate to read a full article by selecting a case study from the list.
* For the full article, the hero image should be displayed as per the `"hero_image"` key.
* For the full article, the title should be displayed as per the `"title"` key.
* For each article, the body content should be displayed as per the array value for the `"sections"` key.
* For each section, the title (if provided in the JSON) should be displayed in a strong font weight to distinguish from the body text. It is read from the section's `"title"` key.
* Each section has a list of body elements (either text or image). These are read from the `"body_elements"` key.
* Text should be displayed in a light font weight to disinguish from the section's title. Text is given as a string in the `"body_elements"` array.
* Images should be displayed in-line in the article, as they appear in the JSON. Images are given as a simple JSON object with the single key `"image_url"`.
* The user should be able to easily return to the full list of case studies (delivered in TAB-001).

# 👾 Dependencies

Please complete the test without the use of third-party dependencies. We want you to demonstrate your knowledge and experience of the iOS eco-system.

# ✨ Putting your stamp on it

No designs are provided. As such, you can put your own creative stamp on the delivered software. You are encouraged to add any nice touches that you feel showcase your abilities. However, the most important thing is that your code works, it is well structured and it meets the acceptance criteria laid out above.

# 🔍 Any Questions

Please don't hesitate to contact us with any questions. It's better to ask clarification questions up front.
