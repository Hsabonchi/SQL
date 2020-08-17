# SQL

- [Indexing the Web—It’s Not Just Google’s Business](https://alistapart.com/article/indexing-the-web-its-not-just-googles-business/)
- [Data Normalization] (Data Normalization).
- [L06 - Index Locking & Latching CMU Database Systems Spring 2017](https://www.youtube.com/watch?v=y8WoIgT_LIQ&list=PLSE8ODhjZXjYgTIlqf4Dy9KQpQ7kn1Tl0&index=6)
- [A Role For Unique constraints with soft delete](https://medium.com/@ibakhsh/a-role-for-unique-constraints-with-soft-delete-4bbf417e442b)
---
The relationships between Entity classes are as follows:

- @ManyToOne Relation
- @OneToMany Relation
- @OneToOne Relation
- @ManyToMany Relation

- @OneToMany Relation:In a one-to-many relationship between Table A and Table B, each row in Table A is linked to 0, 1 or many rows in Table B.
   > In a One-to-Many/Many-to-One relationship, the owning side is usually defined on the ‘many' side of the relationship. It's usually the side which owns the     foreign key.The @JoinColumn annotation defines that actual physical mapping on the owning side.
   >  the value of mappedBy is the name of the association-mapping attribute on the owning side



- @ Many-To-One relation between entities: Where one entity (column or set of columns) is/are referenced with another entity (column or set of columns) which contain unique values. In relational databases these relations are applicable by using foreign key/primary key between tables.


