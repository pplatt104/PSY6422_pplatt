# 

This data is loaded from Storygraph, an app that tracks reading habits. I used my own data from 2024-2026, which is how long I have been actively tracking what I read. This data was exported from my account, and can be found at this link: pplatt_storygraph.csv as an excel spreadsheet that can be imported into r.

Storygraph tracks multiple variables about books logged. One of the most interesting variables is 'Moods'. This variable contains several themes, e.g adventurous, sad, relaxing, etc. that when reviewing books you can add to your profile of that book, to illustrate the feel of it. As I read a wide range of books, I was curious to see which moods appeared the most in my profile, and what I rated books that had these moods.

Therefore this visualisation attempts to look at the moods of books I read plotted against how many stars I rated books that had these moods. This is conceived as a heatmap, where tile colour represents the frequency of this rating being given to that particular mood.

This plot is also interactive, so hovering over tiles gives a number of books rated, instead of relying on the colour scale entirely. This means that not only can you understand immediately any trends by simply looking at the colours displayed, but can also gain a more concrete understanding by viewing the exact number.
