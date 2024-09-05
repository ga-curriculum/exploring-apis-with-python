<h1>
  <span class="headline">Exploring APIs with Python</span>
  <span class="subhead">Setup</span>
</h1>

| Lesson | Duration |
| ------ | -------- |
| Setup  | 15 min   |

## OpenWeatherMap API Key

In this lesson, we'll practice making requests to a third-party API to retrieve weather forecast data. To get started, we'll need an API key to access the weather data. Let's walk through the process of obtaining and setting up your API key.

<img src="./assets/key.png" alt="Key Image" style="width: 300px; height: auto;">

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

## Setup

The practice exercises for this lesson can be found in the `01-apis.py` file of the [Python Flask Exercises](https://git.generalassemb.ly/modular-curriculum-all-courses/python-flask-exercises) repository.

### Prepare Your Environment

1. **Navigate to the Cloned Repository**:

   - After cloning, navigate into the directory of the repository:

   ```bash
   cd python-flask-exercises
   ```

2. **Activate Your Virtual Environment**:

   - Ensure you're using the correct Python environment by activating the `ga-env` environment:

   ```bash
   conda activate ga-env
   ```

   - You should see `(ga-env)` at the beginning of your terminal prompt, indicating that the environment is active.

### Open the Exercises in VS Code

1. **Open VS Code**:

   - Launch Visual Studio Code.

2. **Open the Repository Folder**:

   - In VS Code, go to **File > Open Folder...** and navigate to the directory where you cloned the repository.

   - Select the repository folder (e.g., `python-flask-exercises`) and click **Open**.

3. **Select Your Python Environment**:

   - Ensure that the `ga-env` environment is selected. Press <kbd>Ctrl/Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> to open the Command Palette.

   - Start typing `Python: Select Interpreter` and select it.

   - Choose `ga-env` from the list.

4. **Open the Practice Exercises**:

   - Navigate to the `01-apis.py` file within the cloned repository.

   - Double-click to open the file and review the exercises.
