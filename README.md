MediFlow: encrypted health attributes as composable on-chain state
MediFlow stores four health attributes per patient on Sepolia testnet as euint64 ciphertexts: risk score, condition flags bitmask, age, and medication count. These are encrypted client-side using @zama-fhe/react-sdk's useEncrypt() hook and submitted to PatientRegistry.sol.

The key architectural property: these ciphertexts are composable. Other contracts can read the handles and compute on them without ever seeing the underlying values


MediFlow: encrypted health attributes as composable on-chain state
MediFlow stores four health attributes per patient on Sepolia testnet as euint64 ciphertexts: risk score, condition flags bitmask, age, and medication count. These are encrypted client-side using @zama-fhe/react-sdk's useEncrypt() hook and submitted to PatientRegistry.sol.

The key architectural property: these ciphertexts are composable. Other contracts can read the handles and compute on them without ever seeing the underlying values.
