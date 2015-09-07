## volunteers
id     | name | supervisor_id | permission_group_id
-------|------|---------------|--------------------
1      | Joe  | nil           | 1
2      | Bob  | 1             | 2
3      | Sue  | 1             | 2

## permission_groups
id     | name        | permission_id
-------|-------------|--------------
1      | Head Admin  | 1
2      | Board Member| 2
3      | Volunteer   | 3

## permissions
id     | permissions
-------|----------------
1      | Add, edit, remove, read
2      | Add, edit, read
3      | Add, read

## ballots
id    | location |
------|----------|
1     |    SF    |
2     |    NY    |
3     |    LA    |

##office_types
id    | name     |
------|----------|
1     | Governor |
2     | Mayor    |
3     | Treasurer|


## offices
id | ballot_id | office_type
---|-----------|------------
1  |     1     | 1
2  |     1     | 2
3  |     1     | 3
4  |     2     | 1
5  |     2     | 2
6  |     2     | 3


## candidates
id | name   | office_id | information
---|--------|-----------|------------
 1 |  Jim   |    2      | Info about Jim
 2 |  Bill  |    2      | Info about Bill
 3 |  Ellen |    2      | Info about Ellen
 4 |  Laura |    3      | Info about Laura
 5 |  Peter |    3      | Info about Peter
 6 |  Sam   |    5      | Info about Sam
