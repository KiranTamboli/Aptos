Install CLI : Developer Setup | Aptos Docs (en)
CLI | Aptos Docs (en)
Windows Installation : cli · Releases · aptos-labs/aptos-core (github.com) 
Aptos CLI Release v3.4.1


	Download Zip File
	Extract All in downloads folder only
	Aptos file would be generated 
	Set environment variables
	C:\Users\<username>\Downloads\aptos-cli-3.1.0-Windows-x86_64
	aptos —-version
	3.4.1

Create Package : Create Package (Move) | Aptos Docs (en)
aptos move init --name nameofproject


code . (Open VS Code)
You shud get folder structure created

Update Move.toml : [address section] hello_blockchain = "_"

Add contract file to sources folder : hello_blockchain.move
Abilities: Introduction - The Move Book (move-book.com)
Create a account : aptos init
Update Contract address in Move.toml file 
aptos move compile
aptos move publish
Aptos Explorer (aptoslabs.com)
