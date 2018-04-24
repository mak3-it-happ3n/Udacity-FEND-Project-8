# Neighborhood Map Project

## Description:
A single page web app, using Google maps and Foursquare's API to list all several Points of Interests.

## Start the program:
First install Node.js and download or clone this repository.
Then navigate into the directory project directory and type:
```
npm install
```
once all components have been installed, run the program:
```
npm start
```
Usually a new window will open automatically to display the web app. If you can't see the web app, manually navigate to the following page in your browser: [http://localhost:3000/](http://localhost:3000/)

## Loading the App in Production Mode:
To run the app in production mode (with an active service worker), first run the following:
```
npm run build
```
once in the build directory, start a localhost with python
```
python -m SimpleHTTPServer 8000
```
and finally navigate to [http://localhost:8000](http://localhost:8000)

# Contribution, Licensing, Usage Information
This project has been created purely for the purpose of the _Front-End Web Developer Nanodegree_ course at **UDACITY**.

## MIT License

_Copyright (c) 2018 Christoph Pätzold_

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
