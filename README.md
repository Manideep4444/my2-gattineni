# my2-gattineni
My second repo
# My name is Manideep
###### Favourite spot kedarnath

The temple is situated against the backdrop of breathtaking Himalayan peaks, creating a stunning and serene setting for worship. The picturesque landscape adds to the spiritual experience, making it a unique place for both devotion and natural beauty.<br><br>
The journey to Kedarnath is not only about the destination but also the arduous trek or journey involved. Pilgrims embark on a challenging trek through __rugged terrain__ and changing weather conditions, making the experience more meaningful and fulfilling.<br><br>
The __Kedarnath Temple__ holds immense spiritual significance for Hindus. It is one of the holiest shrines dedicated to Lord Shiva and is considered one of the twelve Jyotirlingas. Pilgrims visit the temple to seek blessings, offer prayers, and perform religious rituals.<br><br>

-----

# Activities that can be at favourite spot

1. Visiting Temple
2. Exploring the temple architecture
3. Treking

# Food available at favourite spot

- Lemon rice
- Sweet
- Dal/Sambar rice

**[MyStats page link](MyStats.md)**

----

# Sports Recommendation Table

A sports recommendation table is a list that provides suggestions related to sports activities. It typically includes information such as the type of sport, why we that recommended that sport, and avg hours to be spend on that sport. This table is often used to help individuals to make decisions about which sports to participate.


| Name of Sport | Reason for Recommending | Hours to spend in a week |
| --- | --- | --- |
| Cricket | Improves all types of skills | 10 hours |
| Volleyball | Improves all types of skills | 5 hours |
| Badminton | Improves all types of skills | 2 hours |
| Football | Improves all types of skills | 3 hours |


-----

# Pithy Quotes
> "Success is not final, failure is not fatal: It is the courage to continue that counts." - *Winston Churchill*
>
> "The only way to do great work is to love what you do." - *Steve Jobs*


-----

# Code Fencing

> [article on stack overflow for Validating age using JQUERY](https://stackoverflow.com/questions/22781994/age-check-by-birthdate-to-exact-date-for-jquery-validate)

```$("#age-form").submit(function(){
	var day = $("#day").val();
	var month = $("#month").val();
	var year = $("#year").val();
	var age = 18;
	var mydate = new Date();
	mydate.setFullYear(year, month-1, day);

	var currdate = new Date();
	currdate.setFullYear(currdate.getFullYear() - age);
	if ((currdate - mydate) < 0){
		alert("Sorry, only persons over the age of " + age + " may enter this site");
		return false;
	}
	return true;
});
```
> [Link to the snippet source](https://css-tricks.com/snippets/jquery/validate-age/)


