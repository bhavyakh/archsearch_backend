<h1 align="center">ArchSearch Backend</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.2-blue.svg?cacheSeconds=2592000" />
</p>

> BACKGROUND - In these difficult days of the ‘Corona Pandemic’ the whole world is hugely affected by the ongoing state which has affected both the mental and physical mindsets of the general population. There has been panic all among the people in the nation especially after the sudden 21-day lockdown announced by the Government.

PROBLEM - Amid this crisis, large gatherings and stampedes at grocery stores totally defy the purpose of this lockdown. Social distancing is key to staying safe and crowding at general stores exposes the people to this virus. This rush for daily supplies could result in further spread of the pandemic. The problem is to prevent crowds while maintaining regular supply to all.

SOLUTION - We have decided to create a user interface in the form of a website/mobile application to fulfill the demands of the public while ensuring their safety. This can be used by any user to (a) book slots for grocery shopping; (b) keep track of stocks in nearby stores; (c) book home deliveries only for veterans; (d) keep track of no. of persons in the respective stores at the moment; (e) generate passes to approach the stores hassle-free.
We are now in recession, it is way worse than the global financial crisis and it is a crisis that requires all of us to come together. This interface prevents the public from crowding, hoarding supplies, leaving homes unnecessarily and spreading the virus.

### ✨ [Demo](https://www.youtube.com/watch?v=z4ave28HYSw)


Backend of ArchSearh app with nodejs
Functioning at https://aqueous-cliffs-40873.herokuapp.com/

<pre>@route   GET api/customer/test
@desc    Tests users route
@access  Public

@route   GET api/customer/register
@desc    Register user
@access  Public

@route   POST api/customer/login
@desc    Login User / Returning JWT Token
@access  Public

@route   /api/customer/current
@desc    Return current user
@access  Private

@route   /api/customer/slot1
@desc    Return current user
@access  Private

@route   GET api/shopkeeper/register
@desc    Register user
@access  Public

@route   GET api/shopkeeper/login
@desc    Login User / Returning JWT Token
@access  Public

@route   POST api/shopkeeper/profile
@desc    Send unavailable
@access  Private
</pre>
