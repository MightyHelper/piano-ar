# Variables
SRC = src/server.ts
DIST = dist/src/server.js

# Targets
$(DIST): $(SRC)
	tsc

build: $(DIST)
run: build
	node $(DIST)

clean:
	rm -rf dist

# Default target
all: run
