### Installation with ZMQ instruction

- Clone zmq  
  ``git clone git@github.com:shroukkhan/mql-zmq.git``
- Copy `mql-zmq/Library/MT5/libsodium.dll` and `mql-zmq/Library/MT5/libzmq.dll` to `MQL5/Libraries` folder    
  ![](./doc_image/lib_folder.PNG)
- Copy `mql-zmq/Include/Mql` and `mql-zmq/Include/Zmq` to `MQL5/Include` folder  
  ![](./doc_image/zmq_include.PNG)
- Create `MQL5/Scripts/ZMQ` folder and copy everything from `mql-zmq/Scripts/` folder to it  
  ![](./doc_image/zmq_scripts.PNG)
- Enable dll import in MQL5  
  ![](./doc_image/mt_dll_import.PNG)
- Compile `MQL5/Scripts/ZMQ/TestZmq.mq5`
  ![](./doc_image/compile_zmq.PNG)
- Run it in MT5 by double clicking it:
  ![](./doc_image/run_script.PNG)
- Done with zmq!
- Now copy `MQL5-JSON-API/Include/*` to `MQL5/Include`
  ![](./doc_image/py_include.PNG)
- Copy `MQL5-JSON-API/Indicators/JsonAPIIndicator.mq5` to `MQL5/Indicators` folder  
  ![](./doc_image/indicator.PNG)
- Copy `MQL5-JSON-API/Experts/JsonAPI.mq5` to `MQL5/Expers` folder and compile it
  ![](./doc_image/compile_jsonapi.PNG)
- Drag it to the chart in MT5 and you should get this popup
  ![](./doc_image/enable_expert.PNG)  