# /db

This is where all manifests for apps are stored. If you want to update your app, submit a PR here. 

See the actual Manny repo [here](https://github.com/Milo123459/manny)

## Contributing

Hi. Glad to see you are interested in adding your app to Manny! We are constantly trying to make Manny better, so, feedback is welcome in the Manny repo linked above.

Alright, adding your app is easy. Simply create a `markdown` file in the DB repo. 

For example, if I have an app called vscode, I create a db/vscode.md file (that is a path).

Inside, we follow a template like this:
```md
# VSCode - Code editing redefined (header! (h1))

## Examples (sub header! (h2))

### Technologies (sub-sub header! (h3))
```

This allows you to write content, and we will render it as such, with headers getting a nice, sturdy red colour, sub headers getting a cool blue and sub-sub headers getting a cool green. Colours are customisable, but, that is in the future roadmap.

Submit a PR, adding your file and enjoy. As soon as it is merged, type `manny update` and then you can type `manny manifest <app_i_added_here>` or `manny <app_i_added_here>` if the name isn't [generic](https://github.com/Milo123459/manny#generic)