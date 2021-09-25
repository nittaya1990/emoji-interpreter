# Emoji Interpreter

## List of Contents
- Descritpion
- Input
- Output
- Processing
- Credit
- Screenshots
- Link

> **Description:** Want to know what an emoji mean then click on an emoji and know it's meaning, more interpret an emoji meaning in mind then click on emoji to check your interpreting skill. One can also search an emoji meaning, if in database else user will get to know. For emoji to be in databse, has to be accepeted by 50 percentile of community members(consensues).

<br>

> **Input:** A user can give input in two ways one by entering an emoji in input section and second by clicking on emojis in display section. In input section user has to enter emoji to check it's meaning, other than emoji every input will be treated as emoji and user is informed with appropriate message. For input there is input constraints such as empty cannot be empty.

<br>

> **Output:** User will get to know emoji meaning if available in database after clicking on emoji display section, if user enters an emoji which is not available then user is informed with message `Emoji not found!!` else with meaning of emoji. Output is text message for the user.

<br>

> **Processing:**
- User has to click on emoji or eneter an emoji to know emoji meaning.
- If user click on emoji, then after that function `getEmojiMeaning` is called, which emoji akes as input argument of `event type` and then searches for emoji meaning in database and display it to the user in output section. For this `getEmojiMeaning` function uses `useState` function()(`setEmojiMeaning`) to get display emoji meaning to the user.
- If user enters an emoji then using function `onChange` emoji meaning is checked in the database if found then appropriate meaning is displayed to the user, else `Emoji not found!!` message. For this function `onChange` uses function `getEmojiMeaning` input argument of `string type` and then similarly uses function `useState` to update the user.

<br>

> **Credit:** Goes to `ReactJS` and `CodeSandbox`.

<br>

> **Screenshots:**
![emoji interpreter home page](https://github.com/shmbajaj/emoji-interpreter/blob/main/home.png?raw=true)
![emoji interpreter clicked on emoji to know it's meaning in display section](https://github.com/shmbajaj/emoji-interpreter/blob/main/emoji_click.png?raw=true)
![emoji interpreter enetered on emoji to know it's meaning in input section, but no emoji found in database](https://github.com/shmbajaj/emoji-interpreter/blob/main/emoji_nf.png?raw=true)

<br>

> **Link:** [Emoji Interpreter](https://ynx7g.csb.app/)
