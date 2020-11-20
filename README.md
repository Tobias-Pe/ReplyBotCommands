# ReplyBot Commands
This bot uses a dictionary which maps expressions to answers.

`<show` Outputs the exact and the wildcard dictionary. If it's over 2000 characters it will output a JSON file.

`<show "searchterm"` Outputs the answers for a certain expression. Outputs answers for both exact and wildcard dictionary.

`<add "expression" "answer"` Adds an exact entry to the dictionary. The bot will search if a chatmessage exactly matches the first parameter of this command and will send in the chat, the second parameter (the answer). (If a message has more than one answer it will randomly choose one of these answers)

`<addw "expression" "answer"` Adds an wildcard entry to the dictionary. The bot will search if a chatmessage contains the expression and will then output the answer like the `<add` command

`<rem "expression" "answer"` Removes the answer for an expression in the exact dictionary.

`<remw "expression" "answer"` Removes the answer for an expression in the wildcar dictionary.

   Tipp: [user] inside quotation marks for a reply will mention the author.
