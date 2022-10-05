# Random-User-API-Performance-Test with Jmeter
### IDE used
    Apache Jmeter 5.5
### API  used for this testing:

|Method|   Url	 | Decription	|Sample Valid Request Body|
|------|---------|--------------|-------------------------|
| GET  |https://random-data-api.com/api/v2/users |User information |  JSON|

## Follow the test strategy
#### Load Test stategy: https://tinyurl.com/2wth7ns8

#### Stress Test strategy: https://tinyurl.com/4rn2jw72

## Run the test in Jmeter
    1. Add a Thread Group inside the Test Plan
    2. Add a HTTP Request inside the Thread Group and use the mentioned API information
    3. Add two listeners 'View Result Tree' and 'Summary Report' inside the HTTP Request
    4. Run the test

## Test Reports:
### Load Test
![TPS_Breakdown](https://github.com/Foysal061/Random-User-API-Performance-Test/blob/main/TPS_Breakdown.png)

### Stress Test
![Bottleneck_Point](https://github.com/Foysal061/Random-User-API-Performance-Test/blob/main/Bottleneck_Point.png)
