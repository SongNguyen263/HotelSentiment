import gzip

with gzip.open('../word2vec-GoogleNews-vectors/GoogleNews-vectors-negative300.bin.gz', 'rb') as f_in:
    content = f_in.read()

with open('../word2vec-GoogleNews-vectors/GoogleNews-vectors-negative300.bin', 'wb') as f_out:
    f_out.write(content)
