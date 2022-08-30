# Reading: Class 13 - Local Storage

1. Why would a developer use local storage for a web application?

   Using local storage makes it possible to store the state of the interface/webpage/webapp, without needing to have or authenticate the user to remote, server storage.

2. What information should not be stored in local storage?

   No sensitive (privacy-wise) information should be saved using local storage, as it is no more secure that a cookie.

3. Local storage can store what type of data? How would you convert it to that type before storing?

   Local storage can only store strings. The methods _JSON.stringify()_ and _JSON.parse()_ can be used to turn an object into a string and back again, respectfully.

## Things I want to know more about

I'd like to look into the methods of encrypting local storage, to improve the security of the data.
