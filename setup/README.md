<h1>
  <span class="headline">Exploring APIs with Python</span>
  <span class="subhead">Setup</span>
</h1>

| Lesson | Duration |
| ------ | -------- |
| Setup  | 15 min   |

## OpenWeatherMap API Key

In this lesson, we'll practice making requests to a third-party API to retrieve weather forecast data. To get started, we'll need an API key to access the weather data. Let's walk through the process of obtaining and setting up your API key.

### Setting Up Your Account

We'll be using the [OpenWeatherMap API](https://home.openweathermap.org/) for this exercise. Follow these steps to get started:

1. **Sign Up for a Free Account**: Go to [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) and sign up for a free account. 

2. **Obtain Your API Key**: After signing up, you'll be provided with an API key. This key is essential for accessing the API, so make sure to copy it and store it securely for future use.

3. **Test Your API Key**: To ensure your API key is working, try making a test request. You can do this by pasting the following URL into your browser, replacing `[ZIP CODE]` with a test zip code and `[API KEY]` with your unique API key:

```text
api.openweathermap.org/data/2.5/weather?zip=[ZIP CODE],us&units=imperial&appid=[API KEY]
```

### Next Steps

Once your API key is set up and working, you'll be ready to move on to our first coding challenge, where we'll make requests to the OpenWeatherMap API to retrieve and work with real weather data.

Don't worry if it takes a little time for the API key to become active—everything should be ready by the time we start coding.
