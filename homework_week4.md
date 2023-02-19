# Homework week 4

## Question 1:
```
SELECT COUNT(*) FROM `de-zoomcamp-375510.production.fact_trips`
WHERE pickup_datetime >= '2019-01-01' AND pickup_datetime < "2021-01-01"
```
=> 61648442

## Question 2:
=> 89.9/10.1

## Question 3:
```
SELECT COUNT(*) FROM `de-zoomcamp-375510.production.stg_fhv_tripdata`
```
=> 43244696 (without removing duplication)

## Question 4:
```
SELECT COUNT(*) FROM `de-zoomcamp-375510.production.fact_fhv_trips`
```
=> 22998722

## Question 5:
=> January
