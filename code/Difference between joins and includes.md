## includes
- performs a left outer join between two tables.
- since it is a left outer join, it may include null values from the left table
- it also loads both the tables in memory
- eager loading
E.g

```
user_comments = Comment.includes(:user)

# May fetch comments that have user_id: nil or orphaned user comments

user_comments.pluck(:user_id)
=> [1, 2, 3, nil]
```

## joins
- performs an inner join between two tables.
- since it is an inner join, it will fetch records that are both present in tables or with matching values in both tables
- does not load both tables in memory
- lazy loading
E.g

```
user_comments = Comment.joins(:user)

# Will only fetch comments where user_id is not null

user_comments.pluck(:user_id)
=> [1, 2, 3]
```


# Pakita sa error
