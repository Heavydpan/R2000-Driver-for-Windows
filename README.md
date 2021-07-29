# R2000-Driver-for-Windows
R2000 Driver for Windows
Beta version
Need BOOST for Windows

std::string TCPScanStart(std::string type, std::uint32_t watchdogtimeout, std::int32_t star_angle);
char* GetTCPPointData();
std::string HttpGet( std::string command);
uint16_t SetPara(std::string sParaName, std::string sPara);
std::string UDPScanStart( std::string LocalIP, std::uint16_t port, std::string type);
char* GetUDPPointData();
std::string GetPara(std::string sPara);
bool disconnect();
bool StopGetting();
bool setScanFrequency(std::uint16_t sf);
bool setSamplesPerScan(std::uint16_t spc);
bool connect(std::string IP);

connect(..)->TcpScanStart(..) or UDPScanStart(..)->GetTCPPointData() or GetUDPPointData()->StopGetting()->disconnect()
Can use function to change para(s).
