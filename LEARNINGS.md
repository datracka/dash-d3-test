# Learnings

This Project is the intent of create a Dash component from react / d3 code. 

The final code is PURE python code together with React for client communication.

- There is a src code (pure React / D3 code)
- There are some scripts that build final output code (in dash_network)
dash_network.dev.js (build with package.json build:js-dev)
dash_network.min.js (build with package.json build:js)
metadata.json (important for building Network.py class)
Network.py classes
package.json (needed to run program)

Note: - package.json build:py was using venv (virtualenv) becasuse we use pipenv I changed executable to python3 directly

The question is.... can we build a pure D3 graph in javascript and get data from server?? 
