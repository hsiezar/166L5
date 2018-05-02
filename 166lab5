SELECT C.pid
FROM Catalog C
WHERE C.cost < 10

SELECT P.pname
FROM Parts P, Catalog C
WHERE P.pid = C.pid AND C.cost < 10

SELECT S.address
FROM Parts P, Catalog C, Suppliers S
WHERE P.pname = 'Fire Hydrant Cap' AND P.pid = C.pid AND C.sid = S.sid

SELECT S.sname
FROM Parts P, Catalog C, Suppliers S
WHERE P.color = 'green' AND P.pid = C.pid AND C.sid = S.sid

SELECT P.pname, S.sname
FROM Parts p, Catalog C, Suppliers S
WHERE P.pid = C.pid AND C.sid = S.sid
