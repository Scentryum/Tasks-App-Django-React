# Tasks App Django React

We're going to use Django Rest Framework with React on the front-end.

---


# How to Run

## Installation
 

To run, you need to install the npm packages and required files for backend

### Django Installation

```
pip install -r requirements.txt
```

### React Installation

```
cd .\react\frontend\
npm install
```


## Running

 First Run the backend by 
 ```
 python.exe ./django/manage.py runserver
```

Then, Run React
```
cd .\react\frontend\
npm run
```

You should be able to use the app.

To Create Apps, simply add the "Add Task" Button.

You should be able to see the created task.

To change the status, just click on the "On Going" or "Done" Buttons.

Exceeded tasks wont change their statuses nor you can update them.

To Update or Delete a task, hover on the task and you'll see two new buttons at the right side of the table.
