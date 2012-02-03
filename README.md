Just simply manually pushing to clojars with:

     scp pom.xml myjar-1.0.jar clojars@clojars.org:

will ensure its uploaded (make sure the SSH keys are the same - I used the ones in ~/.leiningen and copied them to ~/.ssh/