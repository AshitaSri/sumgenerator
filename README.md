# Sumgenerator

Debounce Functionality: Implemented debounce functionality ensures that the sum calculation is triggered only after a brief pause in user input, preventing unnecessary server requests and improving performance.
Asynchronous Fetch: Utilizes the fetch API to asynchronously retrieve the sum from the server without blocking the main thread, providing a seamless user experience.
Sum Calculation: The sum is calculated on the server-side using a designated endpoint (https://sum-server.100xdevs.com/sum) by passing the input numbers as parameters.
Manual Calculation: Users have the option to manually trigger the sum calculation by clicking the "Calculate sum" button, bypassing the debounce delay.
