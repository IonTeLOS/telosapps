# How can I contribute?
Well, you can...
* Suggest new apps to be included in suggestions
* Spread the word about this project, post relevant content in social media
* Report bugs
* Add improvements
* Fix bugs
* Add new translations or fix the current ones
* Add a new theme
* Build a Flatpak or Snap for Waffles
* Create a relevant "recipe" for an AppImage builder
* Last but not least, you can think of your own way to contribute!

# Reporting bugs
The best way to report bugs is to follow these basic guidelines:

* First describe in the title of the issue tracker what's gone wrong.
* In the body, explain a basic synopsis of what exactly happens, explain how you got the bug one step at a time. If you're including script output, make sure you run the script with the verbose flag `-v`.
* Explain what you had expected to occur, and what really occurred.
* Optionally, if you want, if you're a programmer, you can try to issue a pull request yourself that fixes the issue.

# Adding improvements
The way to go here is to ask yourself if the improvement would be useful for more than just a singular person, if it's for a certain use case then sure!

* In any pull request, explain thoroughly what changes you made
* Explain why you think these changes could be useful
* If it fixes a bug, be sure to link to the issue itself.
* Follow the [PEP 8](https://www.python.org/dev/peps/pep-0008/) code style to keep the code consistent.

# Adding a new translation
* To add a new translation, you will have to create a file in each directory listed below named as the first two letters of the language in the ISO format (e.g: for 'english' would be 'en'):
- `waffles/view/resources/locale`
- `waffles/gems/appimage/resources/locale`
- `waffles/gems/arch/resources/locale`
- `waffles/gems/flatpak/resources/locale`
- `waffles/gems/snap/resources/locale`
- `waffles/gems/web/resources/locale`
