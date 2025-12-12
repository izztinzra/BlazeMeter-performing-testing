**A. Justification of Test Plan**

The test plan includes three types of performance tests to understand how the system behaves in different situations:
1. Load Test – checks how the website performs under normal user traffic.
2. Spike Test – checks how the system handles sudden traffic jumps, similar to peak hours or promotions
3. Soak Test – checks whether the system stays stable over time and detects issues like memory leaks.
Using all three tests gives a complete picture of the website’s speed, stability, and performance based on standard industry practices.

**B.Justification of Tool Choice (BlazeMeter)**

BlazeMeter was chosen because:
1. It generates load from the cloud, not limited by local hardware.
2. It fully supports JMeter test scripts.
3. It provides clear graphs, reports, and percentiles.
4. It offers real-time performance monitoring.
5. It requires no installation and is easy to use.
6. It is widely used in industry for performance testing.

Overall, BlazeMeter provides accurate, scalable, and easy-to-understand performance testing results.

**C. Justification of Final Recommendations**

Based on the test results, these improvements are recommended:
2. Test with more users (100–500) for higher load validation.
3. Run longer soak tests (1–2 hours) to detect long-term issues.
4. Simulate real user actions like login or booking flows.
5. Test from multiple regions to evaluate global performance.
6. Optimize images and static files, since bandwidth usage is high.

These steps will help ensure the website can handle peak traffic and maintain stable performance.
