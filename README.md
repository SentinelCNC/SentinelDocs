# Documentation

## Packages

### `encoding`

#### `sha256(string) string`
- Returns the SHA-256 hash of the input string.

#### `sha1(string) string`
- Returns the SHA-1 hash of the input string.

#### `sha512(string) string`
- Returns the SHA-512 hash of the input string.

#### `base64(string) string`
- Encodes the input string to Base64.

#### `base32(string) string`
- Encodes the input string to Base32.

#### `md5(string) string`
- Returns the MD5 hash of the input string.

### `global`

#### `online() int`
- Returns the number of users online.

#### `myrunning() int`
- Returns the number of your running processes.

#### `slaves(string) int`
- Returns the number of slave processes for a given string.

### `colour`

#### `gradient(string, int...) string`
- Gradient the given string with integer values and returns a resulting string.

#### `gif(string, int) string`
- Takes a pathway to a GIF file, resizes and displays the frames of the GIF in the terminal, and repeats the process for a specified number of loops.

#### `img(string, int) void`
- Takes an image file path as an argument, resizes the image to 80x24 pixels, converts it to colored ANSI, and writes the ANSI output to a writer.


### `log`

#### `telegram(string, string) bool`
- Sends a message to a Telegram chat using the Telegram API. Requires the message and chat ID as parameters. Returns `true` if the message is sent successfully, otherwise `false`.

#### `discord(string, string) bool`
- Sends a log message to a Discord webhook with the specified message and webhook URL. Returns `true` if the message is sent successfully, otherwise `false`.

### `padding`

#### `padRight(string, int) string`
- Pads the input string on the right with spaces or zeros to a specified length.

#### `padLeft(string, int) string`
- Pads the input string on the left with spaces or zeros to a specified length.

#### `padcustomRight(string, int, string) string`
- Pads the input string on the right with a custom character to a specified length.

#### `padcustomLeft(string, int, string) string`
- Pads the input string on the left with a custom character to a specified length.

### `time`

#### `format(string) string`
- Formats the given string as a time or date.

#### `unix() int`
- Returns the current Unix timestamp.

#### `expirySeconds() int`
- Returns the number of seconds until an expiry date.

#### `expiryHours() int`
- Returns the number of hours until an expiry date.

#### `expiryDays() int`
- Returns the number of days until an expiry date.

### `user`

#### `length() int`
- Returns the user's length.

#### `height() int`
- Returns the user's height.

#### `ip() string`
- Returns the user's IP address.

#### `username() string`
- Returns the user's username.

#### `id() int`
- Returns the user's ID.

#### `maxtime() int`
- Returns the user's maximum time limit.

#### `cooldown() int`
- Returns the user's cooldown time.

#### `concurrents() int`
- Returns the number of concurrent sessions for the user.

#### `maxsessions() int`
- Returns the user's maximum allowed sessions.

#### `opensessions() int`
- Returns the number of currently open sessions.

#### `theme() string`
- Returns the user's theme.

#### `CanAccess(string) bool`
- Checks if the user can access a specific resource or feature.

## Functions

### `clear()`
- Clears the console or terminal screen.

### `echo(object...)`
- Prints one or more objects to the console.

### `include(string)`
- Includes and executes an external itl file.

### `len(string) int`
- Returns the length of the input string.

### `sleep(int)`
- Pauses the program's execution for the specified number of seconds.

### `cnc() string`
- Returns information about the CNC (Command and Control) server.

### `version() string`
- Returns the version of Sentinel.

### `attackprefix() string`
- Returns the attack prefix or identifier.

### `spinner(string, bool) string`
- Displays a spinner with the given message and an optional status indicator.

## New Functions

### `shake() void`
- Shakes the terminal screen.

### `header(string, string, string) string`
- Centers the text, sets the background to the specified RGB color, and sets the text color to the specified RGB color.

### `ipinfo(string) string`
- Retrieves and displays information about the specified IP address. You can use {{lasttarget}} to get the last target's IP address.

### `table(string, string...) string`
- Displays a table with the specified headers and rows. first string is the table header, and the second string is the table rows. 3rd string is the table header. and so on.
