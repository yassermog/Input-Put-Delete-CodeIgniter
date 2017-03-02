# Input Put Delete CodeIgniter

Extends codeigniter The Input core Library to accept put and delete requests 

There is no $_PUT array Originally Supported

It is useful for implementing Restful API in CodeIgniter 

## Installation

Just Put MY_Input.php file in 

```
application/core/MY_Input.php 
```
 

### Put Form Data : 

You can Get all the Put data :

```
$data=$this->input->put();
```


Get one value from the put array :

```
$id = $this->input->put('id');
```

### Delete Form Data : 

Get all the delete array :

```
$data=$this->input->delete();
```

Get one value from the delete array :

```
$id=$this->input->delete('id');
```
