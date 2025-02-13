# RabbitMQ Python Producer Consumer

This is a simple project demonstrating how to set up a basic RabbitMQ Producer-Consumer system. It sends a "Hello, RabbitMQ!" message to a queue and retrieves it using Python.

---

## Prerequisites

1. **Install RabbitMQ**  
   Follow [RabbitMQ Installation Instructions](https://www.rabbitmq.com/download.html) for your platform. Ensure RabbitMQ is running.

2. **Install Python Dependencies**  
   Install the `pika` library:
   ```bash
   pip install pika
   ```

---

## Project Structure

- **`producer.py`**  
  Sends a "Hello, RabbitMQ!" message to the queue.
- **`consumer.py`**  
  Reads messages from the queue and prints them to the console.

---

## How to Run

1. Start the RabbitMQ server.  
   Ensure RabbitMQ is running on `localhost` (port `5672` by default).

2. Run the Consumer:  
   Start the consumer script to listen for messages:

   ```bash
   python consumer.py
   ```

3. Run the Producer:  
   Send a message to the queue by running:

   ```bash
   python producer.py
   ```

4. Observe Output:  
   The consumer script will display the message received from the queue.

---

## Resources

- [RabbitMQ Official Documentation](https://www.rabbitmq.com/documentation.html)
- [pika Python Library Documentation](https://pika.readthedocs.io/)
