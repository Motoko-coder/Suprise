# Relationship Proposal

class RelationshipProposal:
    def __init__(self, partner_name, proposal_message):
        self.partner_name = partner_name
        self.proposal_message = proposal_message

    def propose(self):
        return f"Dear {self.partner_name},\n\n{self.proposal_message}\n\nYours truly,\n[Your Name]"

# Example usage
partner_name = "Alice"
proposal_message = "I would be honored to spend the rest of my life with you. Will you marry me?"

proposal = RelationshipProposal(partner_name, proposal_message)
print(proposal.propose())
# Suprise
To have suprise stay aware.
