## Run locally
Make sure you have the proper TensorFlow environment.
Set PATH_TO_LOCAL_LOGS and ROOT_PATH_TO_LOCAL_DATA in mnist.py

```shell
>> # Run training
>> python -m mnist
```

## Run on TensorPort cloud

1) You need an account on http://tensorport.com.

2) Install TensorPort CLI and login.
```shell
>> pip install tensorport
>> tport login
```

3) Train the model.
```shell
>> git clone git@github.com:tensorport/mnist.git
>> cd mnist
>> tport create project
>> # Follow instructions.
>> tport train
>> # Choose how many GPU or CPU needed.
```

Now you should be able to login to matrix and see your model being trained!
