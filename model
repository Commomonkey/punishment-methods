STRIKE_STATUSES = (
    ('Strike', 'Strike'),
    ('Warning', 'Warning'),
)

class Strike(models.Model):
    user = models.ForeignKey(User)
    issuer = models.ForeignKey(User)
    reason = models.TextField()
    status = models.CharField(choices=STRIKE_STATUSUS)
