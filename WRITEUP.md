# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

Cost-Effectiveness: App Services provide a more predictable pricing model and reduce the overhead of managing infrastructure.
Ease of Scalability: The built-in scaling features allow for quick adjustments based on traffic, which is crucial for a CMS app that may experience variable load.
High Availability: With Azure managing the infrastructure, you benefit from built-in high availability without the need for complex configurations.
Simplified Workflow: The streamlined deployment process allows for faster iterations and updates, enabling a more agile development environment.

### Assess app changes that would change your decision.

Application Requirements: If you chose to deploy the app using a Virtual Machine (VM), you might need to modify the app to handle more complex infrastructure management tasks, such as configuring the operating system, installing dependencies, and managing security updates. This could require additional development time and expertise.

Control Over Infrastructure: A VM provides more control over the environment, which means you could customize the server settings to optimize performance for your specific application needs. If you were to switch to a VM, you would need to ensure that your app is designed to take advantage of this flexibility, possibly by optimizing configurations or implementing additional monitoring tools.

Scalability Needs: If you anticipate a significant increase in user traffic, you might consider switching to a VM for better scalability options. This would require changes in how your app handles load balancing and resource allocation, potentially leading to a more complex architecture.

Integration with Other Services: Depending on your choice, you may need to integrate additional services. For instance, if you choose a VM, you might need to set up a separate database server or caching layer, which would require changes in your app's architecture and code to connect to these services.

Cost Considerations: If the cost of running a VM becomes a concern, you might need to adjust your app's features or performance expectations to fit within a budget. This could involve simplifying certain functionalities or optimizing resource usage.