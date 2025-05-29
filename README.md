# Custom Role & Permission System (Laravel 12)

## টেবিল গুলো:
- `roles`
- `permissions`
- `role_user`
- `permission_role`

## রিলেশন:
- User -> many Roles
- Role -> many Permissions

## হেল্পার মেথড:
- `$user->hasRole('admin')`
- `$user->hasPermission('edit_post')`

## Middleware:
- `role:admin`
- `permission:edit_post`
- 
*****************************************************************************
Login information
user:  admin@example.com
pass:  password