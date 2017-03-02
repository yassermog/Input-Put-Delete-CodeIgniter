# Input-Put-CodeIgniter

Extends codeigniter input class to accept put and delete requests 

There is no $_PUT array Originally Supported 

Just Put this file in application/core/MY_Input.php 

You can Get all the Put data :

```sh
$data=$this->input->put();
```


Get one value from the put array :

```sh
$data=$this->input->put('id');
```