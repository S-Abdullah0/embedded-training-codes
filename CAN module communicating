#include <SPI.h>
#include <mcp_can.h>

MCP_CAN CAN_SENDER(5);
MCP_CAN CAN_RECEIVER(15);

void setup() {
  Serial.begin(115200);
  delay(1000);

  Serial.println("ESP32 STARTED");

  if (CAN_SENDER.begin(MCP_ANY, CAN_125KBPS, MCP_16MHZ) == CAN_OK) {
    Serial.println("Sender OK");
  } else {
    Serial.println("Sender FAILED");
  }

  if (CAN_RECEIVER.begin(MCP_ANY, CAN_125KBPS, MCP_16MHZ) == CAN_OK) {
    Serial.println("Receiver OK");
  } else {
    Serial.println("Receiver FAILED");
  }

  CAN_SENDER.setMode(MCP_NORMAL);
  CAN_RECEIVER.setMode(MCP_NORMAL);

  Serial.println("CAN READY");
}

void loop() {
  byte data[5] = {'H', 'E', 'L', 'L', 'O'};

  CAN_SENDER.sendMsgBuf(
    0x100,
    0,
    5,
    data
  );

  Serial.println("TX: HELLO");

  delay(1000);
}
