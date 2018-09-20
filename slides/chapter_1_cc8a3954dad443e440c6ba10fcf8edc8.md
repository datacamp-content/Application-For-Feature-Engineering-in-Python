---
title: Insert title here
key: cc8a3954dad443e440c6ba10fcf8edc8

---
## Identifying Missing Data

```yaml
type: "TitleSlide"
key: "928a09180a"
```

`@lower_third`

name: Rob O'Callaghan
title: undefined


`@script`
In the first chapter we took a look at the different types of data one may find when performing an analyses. In this lesson we will explore the concept of messy and missing data, how to find it, and once identified, how to deal with it


---
## How Gaps in Data Occur

```yaml
type: "FullSlide"
key: "e7fde9997f"
```

`@part1`
- Data not being collected properly{{1}} 
- Collection and management errors{{2}} 
- Data intentionally being omitted {{3}}
- Could be created due to transformations of the data {{4}}


`@script`
While in an ideal world every data set you come across would be perfectly complete and contain no gaps. Unfortunately this is rarely the case.
Real world data often has noise or omissions. This can stem from many sources for example::
Data not being collected properly (paper surveys not being filled out correctly)
Collection and management errors Someone transcribing the data making a mistake
Data intentionally being omitted (people may want to skip the age box in  an online form)
Could be created due to transformations of the data (eg average of ???)
But this list is far from comprehensive


---
## Why we care?

```yaml
type: "FullSlide"
key: "8b8075e6ba"
```

`@part1`
- Some models cannot work with nulls{{1}}
- Missing data may be a sign of a wider data issue{{2}}
- Missing data can be a useful feature{{3}}


`@script`
You may wonder why missing data matters so much but it is extremely important to identify and deal with missing data. 
Many machine learning models cannot work with gaps in the data (for example if you were performing linear regression, you would need a value for every row and column you wished to use in your data set)
Missing data may may be indicative of a problem in your data pipeline, if there is consistently missing data from a certain field it it should be investigated and acted upon
Missing data may provide information in itself. For example if the number of children of a person is missing they may have no children.

Now that we have established how data may be incomplete, and why that is an issue, lets work through how one can see if their data set has gaps in it, and where these gaps occur if it does


---
## Final Slide

```yaml
type: "FinalSlide"
key: "5b1a3f3ffa"
```

`@script`


