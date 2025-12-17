# Aviatrix Icons

Official icon pack for Aviatrix cloud networking diagrams and documentation. This collection includes standardized visual assets for multi-cloud architectures across AWS, Azure, GCP, Oracle Cloud, Alibaba Cloud, and hybrid/edge environments.

## Installation

### Direct Download
Download individual icons or clone the entire repository:

```bash
git clone https://github.com/AviatrixSystems/aviatrix-icons.git
```

### npm (coming soon)
```bash
npm install @aviatrix/icons
```

## Icon Organization

Icons are organized by cloud provider:

```
icons/
├── aviatrix/logo/    # Aviatrix brand assets
├── aws/              # Amazon Web Services
├── azure/            # Microsoft Azure
├── gcp/              # Google Cloud Platform
├── oracle/           # Oracle Cloud Infrastructure
├── alibaba/          # Alibaba Cloud
├── edge/             # Edge/Hybrid Cloud
└── misc/             # Partners & utilities (Terraform, Equinix, etc.)
```

## Available Icons

### By Cloud Provider

| Provider | Icons |
|----------|-------|
| **Aviatrix** | Logo variants (horizontal, stacked, gradient, flat, dark mode) |
| **AWS** | Cloud, VPC, Subnet, Gateway, VM, Transit/Spoke variants, NAT, TGW, FireNet |
| **Azure** | Cloud, VNet, Subnet, Gateway, VM, Transit/Spoke variants |
| **GCP** | Cloud, VPC, Subnet, Gateway, VM, Transit/Spoke variants |
| **Oracle** | Cloud, VPC, Subnet, Gateway, VM, Transit/Spoke variants |
| **Alibaba** | Cloud, VPC, Subnet, Gateway, VM, Transit/Spoke variants |
| **Edge** | Site, Network, Gateway, Gateway Group, Transit/Spoke variants |
| **Misc** | Multi-Cloud, Equinix, Megaport, Palo Alto, Terraform, FireNet |

### Common Resource Types

Each cloud provider includes these standard resources where applicable:

- **Cloud** - Provider logo/identifier
- **VPC/VNet** - Virtual private cloud/network
- **Subnet** - Network subnet
- **Gateway** - Network gateway (+ Transit/Spoke variants)
- **VM** - Virtual machine
- **Unmanaged** - Resources not managed by Aviatrix

## Usage

### In HTML
```html
<img src="icons/aws/vpc.svg" alt="AWS VPC" width="64" height="64">
```

### In React
```jsx
import AwsVpc from '@aviatrix/icons/aws/vpc.svg';

function Diagram() {
  return <AwsVpc width={64} height={64} />;
}
```

### In Figma/Design Tools
Import SVG files directly into your design tool of choice.

## File Naming Convention

All icons use kebab-case naming:
- `transit-gateway.svg`
- `unmanaged-vpc.svg`
- `spoke-vnet.svg`
- `multi-cloud.svg`

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on submitting new icons or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Important:** The MIT license applies to the original artwork created by Aviatrix. Third-party trademarks (cloud provider logos, partner logos) remain the property of their respective owners. See [TRADEMARKS.md](TRADEMARKS.md) for details.

## Trademark Notice

This icon pack includes stylized representations of third-party cloud services. All third-party trademarks are the property of their respective owners (AWS, Microsoft, Google, Oracle, Alibaba, HashiCorp, etc.).

These icons are intended for use in network architecture diagrams and technical documentation. Please review each provider's brand guidelines for your specific use case. See [TRADEMARKS.md](TRADEMARKS.md) for full details and links to brand guidelines.

---

Made with care by the Aviatrix team.
