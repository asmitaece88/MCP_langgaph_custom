# Environment setup:
pip install python-dotenv langchain-mcp-adapters langgraph "langchain[openai]" mcp streamlit

# Run in separate terminals:
	Terminal 1 — Custom MCP Server
	
		python mcp_server.py

	Terminal 2 —  MCP Client 
	
		python mcp_client_langgraph.py
		
		or
		

		streamlit run streamlit_app.py

## On running the server and the streamlit app commands , we see this page coming up
<img width="1285" height="506" alt="image" src="https://github.com/user-attachments/assets/4ffec1d9-65ef-48ae-901f-1ac4674667d8" />

On entering any questions , it gives us expected answers

<img width="1340" height="615" alt="image" src="https://github.com/user-attachments/assets/e299b630-b8dc-495c-b3bb-4c7dc6b61ce6" />

<img width="1338" height="613" alt="image" src="https://github.com/user-attachments/assets/4becc16f-8d4b-417c-8da0-867b6f8b3a90" />


