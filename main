#include <discord-cpp/discord-cpp.h>

int main() {
  // Initialize discord client
  discord::Client client;

  // Start the client
  client.Initialize();

  // Loop forever
  while(true) {

    // Set status to "Hacking..." 
    client.UpdateStatus(discord::Status::Online, "Hacking...");

    // Sleep for 5 seconds
    sleep(5);

    // Set status to "Compiling code"
    client.UpdateStatus(discord::Status::Online, "Compiling code");

    // Sleep again
    sleep(5);

  }

  // Shutdown client
  client.Shutdown();

  return 0;
}
