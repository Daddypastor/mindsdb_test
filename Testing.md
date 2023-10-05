# Welcome to the AI Workflow Commands Test


**1. Testing List ML Handlers**

```
SHOW HANDLERS;
```
<img width="875" alt="Screenshot 2022-10-13 at 6 37 13 PM" src="https://github.com/Daddypastor/mindsdb_test/blob/main/show_handlers.JPG?raw=true">

**2. Testing CREATE ML_ENGINE**

```
CREATE ML_ENGINE my_openai_engine
FROM openai
USING
    api_key = '<your opanai api key>';
```
<img width="875" alt="Screenshot 2022-10-13 at 6 37 13 PM" src="https://github.com/Daddypastor/mindsdb_test/blob/main/create_mlengine.JPG?raw=true">


**3. Testing List ML Engines**

```
SHOW ML_ENGINES;

```
<img width="875" alt="Screenshot 2022-10-13 at 6 37 13 PM" src="https://github.com/Daddypastor/mindsdb_test/blob/main/list_engines.JPG?raw=true">


**3. Testing DROP ML_ENGINE**

```
DROP ML_ENGINE ml_engine_name;

```
<img width="875" alt="Screenshot 2022-10-13 at 6 37 13 PM" src="https://github.com/Daddypastor/mindsdb_test/blob/main/drop_ml.JPG?raw=true">


### Results


- [ ] Works Great 💚 (This means that all the steps were executed successfuly and the expected outputs were returned.)

---


