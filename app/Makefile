.PHONY: build-dist run-dist

build-dist:
	./gradlew clean installDist

run-dist: build-dist
	./build/install/app/bin/app

say-hello:
    @echo "Hello, World!"
