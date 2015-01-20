all: test

test:
		@emacs -batch -l ert -l ~/.emacs.d/core/test/configuration-layer-test.el -l ~/.emacs.d/core/test/spacemacs-mode-test.el -f ert-run-tests-batch-and-exit

.PHONY: test
