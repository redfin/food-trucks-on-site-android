# food-trucks-on-site-android

## The San Francisco City website hosts a public data source of food trucks.

[About the data](https://data.sfgov.org/Economy-and-Community/Mobile-Food-Schedule/jjew-r69b)

[About the endpoints](https://dev.socrata.com/foundry/data.sfgov.org/bbb8-hzi6)

Example URL to retrieve list of food trucks: 

[https://data.sfgov.org/resource/jjew-r69b.json?$where=dayorder=1 and start24<='16:00' and end24>'16:00'&$order=applicant](https://data.sfgov.org/resource/jjew-r69b.json?$where=dayorder=1%20and%20start24%3C=%2716:00%27%20and%20end24%3E%2716:00%27&$order=applicant)

Service Root: https://data.sfgov.org/resource/

Food Truck Endpoint: jjew-r69b.json?

Filter by Day and Time of Operation (Example): $where=dayorder=1 and start24<='16:00' and end24>'16:00'

Sort by Business Name: $order=applicant

## Some useful data in the return json is:
```
applicant = Business Name
locationdesc = Description of Location
optionaltext = Usually What Food is Offered
```

Please extend the provided Android app so that it retrieves a list of currently open Food Trucks and presents them in a scrolling list. At least as important as writing code that works is demonstrating clean code and architecture skills.

You may use any resources you like.

## Possible Extra Credit:

Implement pull-to-refresh functionality.

Tap on a Food Truck to show a details screen.

Implement some unit tests.
