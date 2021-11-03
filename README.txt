

# When i Add A Record in Django Default Admin panel of a table, One Function Should be Automatic run:

def save(self, *args, **kwargs):
	#my work
	return super().save(*args, **kwargs)