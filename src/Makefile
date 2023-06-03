# (C) 2023 IIAB
# Part of the 2023 IIAB Games Project


PROJECT="Untitled Strategy Game"
VERSION=1.0.0
VERSIONTITLE="Ulysses S. Grant"

# Main file object
mf = main.cpp

help:
	@echo "Makefile for ${PROJECT} version ${VERSION}, ${VERSIONTITLE}"
	@echo ""
	@echo "Operands [ all | help | clean ]"

all: $(mf)
	@echo "Making... please wait..."
	g++ -o main $(mf)
	make -C ./engine


clean:
	@echo "Cleaning project"
	rm *.o main