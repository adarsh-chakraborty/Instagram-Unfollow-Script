# Instagram Unfollow Script

This is a Simple yet useful script which lets you Unfollow users, (Followings & Followers) on Instagram web.

# Script
```javascript
const x23330 = () => {
	console.log('Executing script');
        var arr = document.getElementsByClassName("sqdOP  L3NKy    _8A5w5    ");

        for (var i = 1, len = arr.length; i < len; i++) {
            arr[i].click();
            document.getElementsByClassName("aOOlW -Cab_   ")[0].click();
        }
	
        setTimeout(() => {
		var scroll_stuff = document.getElementsByClassName("isgrP")[0];
      		scroll_stuff.scrollTop = scroll_stuff.scrollHeight;
		setTimeout(x23330, 600000); // 10 mins
	},3000); 
}
```

# How to use

Just copy the above code and open Instagram on a web browser,

Go to the followings/followers tab and open the followers list.

Press <kbd>Ctrl</kbd><kbd>Shift</kbd><kbd>I</kbd> to open developer console.
Paste the above code in console and hit <kbd>Enter</kbd> then execute the function in console like this.

```javascript
x23330();
```
# Terms of use
- You sure can get a temporarly ban for using it too often or unfollowing too many people in certain time.
- It has 10 mins interval before it will execute again but still don't use it too often.
## Credits

- https://stackoverflow.com/a/53534489/9789315
- Me for making some changes.
