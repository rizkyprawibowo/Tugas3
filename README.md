BEGIN TRANSACTION;
CREATE TABLE IF NOT EXISTS "costumer" (
	"id"	INTEGER NOT NULL,
	"nama_pelangan"	TEXT,
	"alamat"	TEXT,
	"email"	TEXT,
	PRIMARY KEY("id" AUTOINCREMENT)
);
CREATE TABLE IF NOT EXISTS "produck" (
	"id "	INTEGER NOT NULL,
	"sku"	TEXT,
	"nama_produck"	TEXT,
	"kategoril"	TEXT,
	PRIMARY KEY("id " AUTOINCREMENT)
);
INSERT INTO "costumer" VALUES (1,'ikbal','serang','ikbal@gmail.com');
INSERT INTO "costumer" VALUES (2,'novi','serang','novi@gmail.com');
INSERT INTO "costumer" VALUES (3,'ajeng','serang ','ajeng@gmail.com');
INSERT INTO "costumer" VALUES (4,'raka','serang','raka@gmail.com');
INSERT INTO "costumer" VALUES (5,'andika','serang','andika@gmail.com');
INSERT INTO "produck" VALUES (1,'rm 001','ramen','mmakanan');
INSERT INTO "produck" VALUES (2,'ss 002','sushi','makanan');
INSERT INTO "produck" VALUES (3,'bb 003','bento','makanan');
INSERT INTO "produck" VALUES (4,'mlo 004','minuman','minuman');
INSERT INTO "produck" VALUES (5,'fnta 005','minuman','minuman');
COMMIT;

