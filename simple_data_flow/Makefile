VER=1.0
TAG=simple-data-flow:$(VER)

all: build run

build:
	docker build -t $(TAG) .

run:
	docker run --rm $(TAG)

clean:
	docker image rm $(TAG)
