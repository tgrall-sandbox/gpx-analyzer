# GPX Analyzer

A Java 21 library for analyzing GPX (GPS Exchange Format) files.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Java Version](https://img.shields.io/badge/Java-21-orange.svg)](https://openjdk.org/projects/jdk/21/)

## Overview

This library provides tools and utilities to parse, analyze, and manipulate GPX files, which are commonly used for storing GPS data including waypoints, tracks, and routes.

## Requirements

- Java 21 or higher
- Maven 3.6 or higher

## Building the Project

```bash
mvn clean compile
```

## Running Tests

```bash
mvn test
```

## Packaging

```bash
mvn package
```

## Project Structure

```
src/
├── main/
│   └── java/
│       └── org/
│           └── windr/
│               └── App.java
└── test/
    └── java/
        └── org/
            └── windr/
                └── AppTest.java
```

## Features

- **GPX File Parsing**: Parse GPX files and extract GPS data
- **Data Analysis**: Analyze tracks, waypoints, and routes
- **Export Capabilities**: Export processed data in various formats

## Usage

```java
import org.windr.App;

public class Example {
    public static void main(String[] args) {
        // Your GPX analysis code here
        App.main(args);
    }
}
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or issues, please create an issue in the [GitHub repository](https://github.com/tgrall-sandbox/gpx-analyzer).
