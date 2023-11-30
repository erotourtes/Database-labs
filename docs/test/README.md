# Тестування працездатності системи

Для тестування системи використовувався `curl`

Був реалізований доступ до таблиць: **User**, **Access**, **Post** - із примітивним доступом за ролями


#### Nest Startup Log
<p>
    <img src="./images/start_success.png">
</p>

## Початкове наповнення бази даних
<p>
    <img src="./images/start_db.png">
</p>

## User

### Get (All)
<p>
    <img src="./images/get(all)_user.png">
</p>

### Post
<p>
    <img src="./images/post_user.png">
</p>

### Get/Id
<p>
    <img src="./images/get(id)_user.png">
    <img src="./images/get(id)_user_failed.png">
</p>

###  Patch
<p>
    <img src="./images/patch_user.png">
</p>

###  Delete
<p>
    <img src="./images/delete_user.png">
    <img src="./images/delete_user_failed.png">
</p>

## Access

### Get (All)
<p>
    <img src="./images/get(all)_access.png">
    <img src="./images/get(all)_access_failed.png">
</p>

### Post
<p>
    <img src="./images/post_access.png">
</p>

### Get/Id
<p>
    <img src="./images/get(id)_access.png">
</p>

###  Patch
<p>
    <img src="./images/patch_access.png">
</p>

###  Delete
<p>
    <img src="./images/delete_access.png">
</p>

## Post

### Get (All)
<p>
    <img src="./images/get(all)_post.png">
</p>

### Post
<p>
    <img src="./images/post_post.png">
</p>

### Get/Id
<p>
    <img src="./images/get(id)_post.png">
</p>
<p>Access is automatically added on post request</p>
<p>
  <img src="./images/get(id)_post_access.png">
</p>

### Patch
<p>
    <img src="./images/patch_post.png">
    <img src="./images/patch_post_failed.png">
</p>

### Delete
<p>
    We have added constraints to the table, so we can not delete it  
</p>
<p>
    <img src="./images/delete_post.png">
</p>
