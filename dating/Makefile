dating-server:
	$(TROUPE)/bin/troupec dating-server.trp -o ./out/dating-server.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-server.js --id=../ids/id-server.json --trustmap=../trustmaps/GoT.json --aliases=aliases.json

dating-client:
	$(TROUPE)/bin/troupec dating-client.trp -o ./out/dating-client.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-client.js --trustmap=../trustmaps/client.json --id=../ids/id-alice.json

dating-bob:
	$(TROUPE)/bin/troupec dating-bob.trp -o ./out/dating-bob.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-bob.js --trustmap=../trustmaps/bob.json --id=../ids/id-bob.json

dating-mal:
	$(TROUPE)/bin/troupec dating-malicious.trp -o ./out/dating-malicious.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-malicious.js --trustmap=../trustmaps/malicious.json --id=../ids/id-malicious.json

dating-mali:
	$(TROUPE)/bin/troupec dating-mali.trp -o ./out/dating-mali.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-mali.js --trustmap=../trustmaps/mali.json --id=../ids/id-mali.json

dating-clark:
	$(TROUPE)/bin/troupec dating-clark.trp -o ./out/dating-clark.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-clark.js --trustmap=../trustmaps/clark.json --id=../ids/id-clark.json
