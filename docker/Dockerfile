FROM rust:latest

# Install required dependencies
RUN apt-get update && apt-get install -y \
    libgsl-dev \
    libclang-dev

RUN cargo install rust-bio-tools

# Set the entrypoint command
CMD ["bash"]