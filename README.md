# WBDS-Application-Spring_Security_Database
[Bài tập] Áp dụng Spring Security trong thực tế có CSDL with Spring Boot


insert into app_user(user_id, user_name, encrypted_password, enabled)
VALUES (1, 'dbadmin1', '$2a$10$PrI5Gk9L.tSZiW9FXhTS8O8Mz9E97k2FZbFvGFFaSsiTUIl.TCrFu', 1);
insert into app_user(user_id, user_name, encrypted_password, enabled)
VALUES (2, 'dbuser1', '$2a$10$PrI5Gk9L.tSZiW9FXhTS8O8Mz9E97k2FZbFvGFFaSsiTUIl.TCrFu', 1);

insert into app_role(role_id, role_name)
VALUES (1, 'role_admin');
insert into app_role(role_id, role_name)
VALUES (2, 'role_user');

insert into user_role(id, role_id, user_id)
VALUES (1, 1, 1);
insert into user_role(id, role_id, user_id)
VALUES (2, 2, 1);
insert into user_role(id, role_id, user_id)
VALUES (3, 2, 2);
