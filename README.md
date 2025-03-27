# Nix Bitcoin Patches

This repository contains Nix package scripts for building Bitcoin Core with various patches in a streamlined manner. It allows developers and researchers to easily apply and test different patches on Bitcoin Core without manually modifying the source.

## Repository Structure
```
.
├── default.nix        # Main Nix expression for building Bitcoin Core with patches
├── patches/           
│   ├── patch1.diff   
│   ├── patch2.diff    
│   └── ...
└── README.md         # This documentation
```

## Getting Started
### Prerequisites
Ensure you have Nix installed on your system. If not, install it using:
```sh
curl -L https://nixos.org/nix/install | sh
```

### Building Bitcoin Core with Patches
Clone the repository and navigate into it:
```sh
git clone https://github.com/your-username/nix-bitcoin-patches.git
cd Nix_packages
```

Run the build command:
```sh
nix-build
```
This will fetch Bitcoin Core, apply the patches, and compile it using Nix.

## Adding to the older Patches
1. Modify `default.nix` to include the new patch.
2. Run `nix-build` to apply and compile with the new patch.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request if you have improvements or new patches.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

