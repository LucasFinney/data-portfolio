## Inner Join
- [[Inner Merge Example]]
- A *and* B
![[Pasted image 20260316103559.png|284]]
- New dataset has all columns from both A and B, all rows with a matching value in the "on" column present in both datasets

## Left Join
- [[Left Merge Example]]
- A or (A and B)
![[Pasted image 20260316103817.png|338]]
- New dataset has all columns from both A and B, all rows from A, and all rows from B with an "on" match to A
## Right Join
- [[Right Merge Example]]
- B or (A and B)
![[Pasted image 20260316103948.png|276]]
- New dataset has all columns from both A and B, all rows from B, and all rows from A with an "on" match to B

## Outer Join
- [[Outer Merge Example]]
- A or B
![[Pasted image 20260316104117.png|329]]
- New dataset has all columns from both A and B, and all rows from A as well as B

## Semi-Join
- [[Semi-Join Example]]

- Use the "on" column of the right table as an inclusionary filter for the rows of the left table
	- Return rows of the left table with a matching "on" column value in the right table
- Returns *only* the columns of the left table

| Table 1 |     |     | Table 2 |     | Result |     |
| ------- | --- | --- | ------- | --- | ------ | --- |
| A       | B   |     | B       |     | A      | B   |
| A1      | B1  |     | B1      |     | A1     | B1  |
| A2      | B2  |     | B1      |     | A3     | B3  |
| A3      | B3  |     | B3      |     |        |     |
## Anti Join
- [[Anti-Join Example]]
- Use the "on" column of the right table as an exclusionary filter for the rows of the left table
	- Return rows of the left table *without* a matching "on" column value in the right 
- Returns *only* the columns of the left table

| Table 1 |     |     | Table 2 |     | Result |     |
| ------- | --- | --- | ------- | --- | ------ | --- |
| A       | B   |     | B       |     | A      | B   |
| A1      | B1  |     | B1      |     | A1     | B1  |
| A2      | B2  |     | B1      |     | A3     | B3  |
| A3      | B3  |     | B3      |     |        |     |
