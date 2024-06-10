# Report for Assignment 1

## Project chosen

### Name: PyGame Menu

### URL: https://github.com/ppizarror/pygame-menu

#### Programming language: Python

## Number of lines  + Tool  

39349 python lines counted using lizard

How to: 

``` ruby
    > pip install lizard

    > lizard -l python # -l chooses the lines of the language lizard should count
```

![Screenshot_6](https://github.com/DavidGilson24/pygame-menu-SEP/assets/100478140/a985c777-e944-470c-8ca8-2a0959a6a01e)
![Screenshot_5](https://github.com/DavidGilson24/pygame-menu-SEP/assets/100478140/18c3587a-36bb-4ad3-b4ab-dfc2fa303900)


## Coverage measurement with existing tool

#### Tool Used: coverage

How to: 

``` ruby
    > pip install coverage


    > coverage run -m pytest # in tests folder


    > coverage report  # or "coverage html" for a nice representation
```

#### Or for a more in-depth analysis:


``` ruby

    > coverage run -m unittest discover #in root folder


    > coverage report # or "coverage html" for a nice representation

```

PS: Both end up giving back the same coverage report


### Results:

![Screenshot_2](https://github.com/DavidGilson24/pygame-menu-SEP/assets/100478140/8698f8f8-330a-4ac2-babe-3554187c64b1)
![Screenshot_1](https://github.com/DavidGilson24/pygame-menu-SEP/assets/100478140/125395e1-f604-4549-ab21-81c8980bbb9e)

#### For 'coverage html'

![Screenshot_3](https://github.com/DavidGilson24/pygame-menu-SEP/assets/100478140/3795d50d-1b12-4027-af7e-db679bde2245)
![Screenshot_4](https://github.com/DavidGilson24/pygame-menu-SEP/assets/100478140/17582942-b4c6-4936-ae77-f94ddaf07f4b)

## Coverage measurement with our own "tool"

### David Gilson:

Original code for Method 'clear' and method '_format_hex':

<img width="197" alt="Original codepng" src="https://github.com/DavidGilson24/pygame-menu-SEP/assets/100478140/88a0bb0d-0f6b-4c94-af6f-f036d6f3bc60">
<img width="345" alt="Original code 2png" src="https://github.com/DavidGilson24/pygame-menu-SEP/assets/100478140/29659f39-3ac6-4f4b-930a-43a54f3ff95c">

Changed + added code:

<img width="323" alt="Screenshot_2" src="https://github.com/DavidGilson24/pygame-menu-SEP/assets/100478140/952d974e-560d-4643-99c8-c0749a67decd">
<img width="419" alt="Screenshot_3" src="https://github.com/DavidGilson24/pygame-menu-SEP/assets/100478140/b328dff1-bf9e-4e79-b5d8-5f1a2e790578">
<img width="600" alt="Screenshot_4" src="https://github.com/DavidGilson24/pygame-menu-SEP/assets/100478140/e56524f4-dfd6-48f7-b468-b3fd5222a867">
<img width="809" alt="Screenshot_6" src="https://github.com/DavidGilson24/pygame-menu-SEP/assets/100478140/8a43c69c-d16e-47f2-9eaf-e62948e04d67">

#### Output to TXT file:

<img width="233" alt="Screenshot_7" src="https://github.com/DavidGilson24/pygame-menu-SEP/assets/100478140/d64e7c7b-9ef0-4e62-b4c0-913052a6b198">

## Coverage improvement

-- NOT DONE YET

<!-- ### Individual tests

<The following is supposed to be repeated for each group member>

<Group member name>

<Test 1>

<Show a patch (diff) or a link to a commit made in your forked repository that shows the new/enhanced test>

<Provide a screenshot of the old coverage results (the same as you already showed above)>

<Provide a screenshot of the new coverage results>

<State the coverage improvement with a number and elaborate on why the coverage is improved>

<Test 2>

<Provide the same kind of information provided for Test 1>

### Overall

<Provide a screenshot of the old coverage results by running an existing tool (the same as you already showed above)>

<Provide a screenshot of the new coverage results by running the existing tool using all test modifications made by the group>

## Statement of individual contributions

<Write what each group member did>

-->


Install Instructions
--------------------

Pygame-menu can be installed via pip. Simply run:


    $> pip install pygame-menu -U

To build the documentation from a Git repository:


    $> clone https://github.com/ppizarror/pygame-menu
    $> cd pygame-menu
    $> pip install -e ."[docs]"
    $> cd docs
    $> make html
