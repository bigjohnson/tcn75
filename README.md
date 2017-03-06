# tcn75
Microchip thermometer tcn75 Arduino library
Read datasheet from http://www.microchip.com/wwwproducts/en/TCN75
    
    instantiate the class with the address of the thermomethre
    tcn75(int myaddress);

    float readTemperature();
    float readHisteresys();
    float readSetPoint();
    void writeSetPoint(float temperatura);
    void writeHisteresys(float temperatura);

    read datasheet for use
    byte readConfig();
    void writeCmptrInt(bool cmptrint);
    void writeShutdown(bool powermode);
    void writePolarity(bool polarity);
    void writeFault(byte fault);
