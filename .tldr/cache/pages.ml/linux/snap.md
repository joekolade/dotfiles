# snap

> സ്നാപ്പ് സെൽഫ് കൺറ്റൈൻഡ് പാക്കേജുകൾ നിയന്ത്രിക്കുവാനുള്ള യൂട്ടിലിറ്റി.
> `apt` നോട് സാദൃശ്യമുള്ളത്.
> കൂടുതൽ വിവരങ്ങൾ: <https://manned.org/snap>.

- ഒരു പാക്കേജ് സെർച്ച് ചെയ്യുവാൻ:

`snap find {{പാക്കേജിന്റെ_പേര്}}`

- ഒരു പാക്കേജ് ഇൻസ്റ്റാൾ ചെയ്യുവാൻ:

`snap install {{പാക്കേജിന്റെ_പേര്}}`

- ഒരു പാക്കേജ് അപ്ഡേറ്റ് ചെയ്യുവാൻ:

`snap refresh {{പാക്കേജിന്റെ_പേര്}}`

- ഒരു പാക്കേജ് മറ്റൊരു ചാനലിലേക്ക് അപ്ഡേറ്റ് ചെയ്യുവാൻ (ട്രാക്ക്, റിസ്ക്, ബ്രാഞ്ച്):

`snap refresh {{പാക്കേജിന്റെ_പേര്}} --channel={{ചാനൽ}}`

- എല്ലാ പാക്കേജുകളും അപ്ഡേറ്റ് ചെയ്യുവാൻ:

`snap refresh`

- ഇൻസ്റ്റാൾ ചെയ്യപ്പെട്ട സോഫ്ട്‍വെയറുകൾ കാണുവാൻ:

`snap list`

- ഒരു പാക്കേജ് അൺഇൻസ്റ്റാൾ ചെയ്യുവാൻ:

`snap remove {{പാക്കേജിന്റെ_പേര്}}`

- സിസ്റ്റത്തിലെ സ്നാപ്പ് ചേഞ്ചുകൾ അറിയുവാൻ:

`snap changes`