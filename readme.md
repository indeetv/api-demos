# Watch API Demo

This is a demo of Indee Watch 2.1 API.   This is a simple HTML page that loads all the
projects and videos associated with a given FYC token and displays them in a simple table.

# Caution 

**This code is for demonstration purpose only.**

Please do not use our API keys on client side applications.  The API key should
be stored securely on your servers and  should be used to establish the initial
session through the ```verify API``

# How to run the demo

The entire code resides in a single HTML file ```index.html```.  You should
serve this file through a HTTP server on your localhost to ensure that there are no CORS errors.

## Code changes

* please replace ```API_KEY_PLACEHOLDER``` with the provided API key
* Please replace ```ACCESS_PIN_PLACEHOLDER``` with your FYC token

## Running the demo

Running this demo on port 3000

## For example - 

If you have python installed, 

```bash
python -m SimpleHTTPServer 3000
```

If you have a node development environment.


```bash
npx http-server --port 3000
```

Now if you open [http://localhost:3000](http://localhost:3000) on your browser.
You should be able to see the projects and videos.

# License

This demo repository is licensed under the following terms.


Copyright 2024 Indee Technologies Inc.,

Licensed under the Apache License, Version 2.0 (the "License"); you may not use
this file except in compliance with the License. You may obtain a copy of the
License at

       http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed
under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied. See the License for the
specific language governing permissions and limitations under the License.
