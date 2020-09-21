# MagicMirror² JokeAPI module
This is a module for `MagicMirror²`; the purpose of the module is to show you jokes from the JokeAPI.

## Installation
1.  Clone this repository into your MagicMirror `modules` folder.
2.  Edit your configuration file under `config/config.js` with the following configuration.
```
{
    module: 'MMM-JokeAPI',
    position: 'middle_center',
    config: {
        category: "Programming"
    }
}
```

### Preview
![Screenshot](screenshot.png)



## Configuration options

| Option                 | Description
|------------------------|-----------
| `category`          | The list of module names that are controlled by this module.<br>Possible values:<br>1.  `Programming`<br>2.  `Miscellaneous`<br>3.  `Dark`<br>4. `Pun`<br>5.  `Any`<br><br> **Type:** `string` <br>**Default value:** `Programming`
| `fetchInterval`| How often (in milliseconds) a new joke should be fetched.<br><br> **Type:** `number` <br>**Default value:** `60 * 1000`
| `blacklistFlags`| Black list flags. <br>Possible values:<br>1. `nsfw`<br>2. `religious`<br>3. `political`<br>4. `racist`<br>5. `sexist`<br><br> **Type:** `string` <br>**Default value:** `nsfw`


#### Credits
MagicMirror²:   [MagicMirror²](https://github.com/MichMich/MagicMirror)
JokeAPI:    [JokeAPI](https://sv443.net/jokeapi)
