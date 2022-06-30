https://gist.github.com/phortuin/2fe698b6c741fd84357cec84219c6667

Dung nhung cau lenh nay oke:

- `brew uninstall postgresql`
- `brew install postgresql@13`
- `brew services start postgresql@13`
- `brew link postgresql@13 --force`

https://www.youtube.com/watch?v=fGOsgMcTP2I
	
<a href="https://www.postgresqltutorial.com/postgresql-administration/psql-commands/">Practical psql Commands</a>

## Command line: 
1. `psql --version`
##### 2.  `psql postgres` : truy cap vap postges (muon dung postgres thi phai vao postgres truoc)
3. `\du` : lists database roles
4. `\l` : danh sach user va database
5. `\conninfo` : xem thong tin ket thoi voi postgres
6. `psql -l (psql --list)` : hien danh sach db, xong roi thoat
7. `CREATE ROLE abc WITH LOGIN PASSWORD 'abc123'`;
8. `ALTER ROLE abc CREATEDB;`
9. `CREATE DATABASE abc;`
