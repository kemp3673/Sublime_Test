# Sublime_Test

<p> Open the index.html file in your browser to see the results.</p>

<p><b>NOTE:</b> I did not include the time I took to source images in this time, as I operated on the belief that image files would most likely be provided on a real world project, but this time was fairly minimal.</p>

<h3>Things That I would do differently</h3>
<ul>
  <li>Given more time, I would have loved to have taken a slightly different approach to the splash component images. I ended up spending a bit more time than I would have liked playing around with them trying to get them to line up like the example provided. They currently are not great on responsiveness, I had debated having them maintain the same aspect ratio and overflowing off the page as the screen shrunk, but elected to bypass that for time as I had already spent a chunk of the time on the images.</li>
  <li>I am not completely satisfied with buttons on the page. I did add hover and click effects to them, but if I had more time I would go back and adjust them slightly as I find the size to be a bit too big looking at them after the fact.</li>
  <li>For the contact form input, I ended up going with a fair bit wider of an input element. To remedy this, I would make it shorter and adjust images a bit to compensate for the gap it would create.</li>
  <li>I found the footer to be a very fun exercise. I could not quite get the border around the instagram icon to become a gradient. Given more time, I would have liked to have taken a shot at that again. As I think I was heading down the correct solution but called it, in order to save time.</li>
  <li>I had attempted to keep responsiveness in mind as I worked, but some areas are definitely better than others in that regard. I worked in a desktop first build pattern in order to mimic the example image. I did ensure the the nav bar collapsed to a hamburger menu when the screen was no longer wide enough to comfortably hold all  the nav items. I did not, however, implement a side menu that would open and close when the hamburger was selected. I also ensured that the grid solution I used for the communities component wrapped to accommodate smaller screen sizes, however I would have liked to have found a better solution that would center the wrapped logos instead of left justifying them. I am thinking flex-box may have been the better approach to this problem.</li>
  <li>For the social media icons in the footer, I had implemented css to change coloring of the border and text when hovered. I think a better approach would be to have the hover action change the opacity to around 0.6 in order to make it slightly transparent to darken the icon as well, since currently that is the only part of the element that does not change coloring when hovered.</li>
</ul>

<h3> Plans for components I did not make it to.</h3>

<ul>
  <li>"By The Numbers" seemed to be a pretty straight forward section. I would set the background color of the container to the dark gray, then added a background image of a transparent clip-art with background position property set to right bottom. Should the clip-art have been white as I had expected, I would set the opacity of the clip-art to be slightly transparent using the background color to darken the overall image.</li>
  <li>The image carousel component is one that I had wished I had time to get to. I have never actually performed this with raw html, css, js before and was excited to give it a go. My plan was to add placement aliases "first, second, third" to the element id of the components with js adding and removing the id as the user navigated through the images. With the dots, I planned to utilize a similar approach to add or remove "active" to the class of the particular dot that would be active to allow css to slightly scale and change the color of that element.</li>
  <li>The last component, "Interested in one..." I had planned to reuse a lot of the similar logic from the splash component as they share a lot in common. </li>
</ul>