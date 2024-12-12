訪問していただきありがとうございます。 （fullstack, blockchain developer.）
Greetings! 

```rust
struct BlockchainDev {
    languages: Vec<&'static str>,
    tools: Vec<&'static str>,
    currently_learning: &'static str,
    fun_fact: &'static str,
}

impl BlockchainDev {
    fn new() -> BlockchainDev {
        BlockchainDev {
            languages: vec!["Solidity", "Rust", "Go"],
            tools: vec!["Ethereum", "Solana", "Polkadot"],
            currently_learning: "ZK-Rollups & Layer 2 Scaling",
            fun_fact: "I once explained blockchain to my grandma using Lego blocks. She’s now a Bitcoin HODLer.",
        }
    }

    fn build_smart_contract(&self) {
        println!("Writing immutable code...");
        println!("Deploying to the blockchain...");
        println!("Praying for no gas fee spikes...");
    }
}

fn main() {
    let chain_dev = BlockchainDev::new();
    chain_dev.build_smart_contract();
}

```
To the end with blockchain development~

大切な人と大切な事を大切に...
